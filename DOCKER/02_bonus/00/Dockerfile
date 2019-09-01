FROM debian

MAINTAINER jmacgyve <jmacgyve@at-d1.21-school.ru>

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat