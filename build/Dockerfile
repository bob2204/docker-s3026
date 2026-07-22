FROM debian:13
RUN  groupadd docker \
  && useradd -m -s /bin/bash bob
USER bob
WORKDIR /home/bob
RUN  echo coucou > data.txt
