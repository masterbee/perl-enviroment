FROM perl:latest

RUN mkdir -p /usr/src/local
    
WORKDIR /usr/src/local

COPY cpanfile* /usr/src/local

RUN cpanm --installdeps .
