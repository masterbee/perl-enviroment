FROM perl:5.30

RUN mkdir -p /usr/src/local
    
WORKDIR /usr/src/local

COPY cpanfile* /usr/src/local

RUN cpanm --installdeps .
