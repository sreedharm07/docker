FROM    centos:7
RUN     yum install httpd -y
#CMD       ["google.com"]
ENTRYPOINT   ["httpd","-DFOREGROUND"]

ENV     project robo
ENV     name   sri
ENV     team  devops

ADD     sample.txt /opt
LABEL   name="srii" \
        proj="robo"
EXPOSE  80
RUN     adduser devops

USER    devops