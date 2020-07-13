FROM debian:stable-slim

RUN apt update && apt-get -y install \
  ncat curl libaio1 libdbd-mysql-perl rsync \
  libcurl4 libcurl4-openssl-dev libev4 \
  && apt-get clean && rm -rf /var/lib/apt/lists/*

RUN curl -o xtrabackup.deb https://www.percona.com/downloads/Percona-XtraBackup-LATEST/Percona-XtraBackup-8.0.13/binary/debian/buster/x86_64/percona-xtrabackup-80_8.0.13-1.buster_amd64.deb && dpkg -i xtrabackup.deb && rm xtrabackup.deb
  
RUN curl -o mysql-apt-config_0.8.15 -1_all.deb https://repo.mysql.com/mysql-apt-config_0.8.15-1_all.deb && dpkg -i mysql-apt-config_0.8.15 -1_all.deb && rm mysql-apt-config_0.8.15 -1_all.deb