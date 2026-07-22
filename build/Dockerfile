FROM debian:13
COPY entrypoint.sh /
ARG  USER=bob
RUN  groupadd docker \
  && useradd -m -s /bin/bash $USER
USER $USER
WORKDIR /home/$USER
RUN  echo coucou > data.txt
ENTRYPOINT ["/entrypoint.sh"]
CMD ["echo","Coucou"]
