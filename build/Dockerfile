FROM debian:13
ARG  USER=bob
RUN  groupadd docker \
  && useradd -m -s /bin/bash $USER
USER $USER
WORKDIR /home/$USER
RUN  echo coucou > data.txt
