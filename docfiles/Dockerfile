FROM    centos:7
RUN     pwd
#CMD       ["google.com"]
#ENTRYPOINT   ["ping","-c3"]

ENV     project robo
ENV     name   sri
ENV     team  devops

ADD     sample.txt /opt
LABEL   name="srii" \
        proj="robo"
EXPOSE  80
RUN     adduser devops

USER    devops

