FROM centos
RUN yum install wget -yum
#RUN apt-get update
#RUN apt-get -y install git
#RUN mkdir vue-pro
#RUN cd vue-pro

#RUN git clone https://github.com/bailicangdu/vue2-elm.git
#RUN git clone https://github.com/bailicangdu/node-elm.git
#RUN git clone https://github.com/bailicangdu/vue2-manage.git
#RUN git clone https://github.com/bailicangdu/vue2-happyfri.git
#RUN git clone https://github.com/bailicangdu/react-pxq.git
#RUN git clone https://github.com/bailicangdu/native-xdm.git


RUN wget https://dl.k8s.io/v1.19.0/kubernetes.tar.gz
RUN wget https://dl.k8s.io/v1.19.0/kubernetes-client-linux-amd64.tar.gz
RUN wget https://dl.k8s.io/v1.19.0/kubernetes-server-linux-amd64.tar.gz
RUN wget https://dl.k8s.io/v1.19.0/kubernetes-node-linux-amd64.tar.gz

#RUN wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-7.8.1-x86_64.rpm
#RUN wget https://artifacts.elastic.co/downloads/kibana/kibana-7.8.1-x86_64.rpm
#RUN wget https://artifacts.elastic.co/downloads/logstash/logstash-7.8.1.rpm

#FROM python:3.7-alpine
#WORKDIR /usr/src/app
#COPY requirement.txt ./

#RUN apk --no-cache add mariadb-connector-c-dev

#RUN apk --no-cache add --virtual .build-deps \
#    build-base \
#    mariadb-dev \
#    && pip install -r requirement.txt -i https://pypi.tuna.tsinghua.edu.cn/simple \
#    && rm -rf .cache/pip \
#    && apk del .build-deps

#COPY ./font/ /usr/local/lib/python3.7/site-packages/reportlab/fonts/