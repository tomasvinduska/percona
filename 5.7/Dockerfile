################################################################################
# Base image
################################################################################

FROM percona:5.7

## Environments
ENV TIMEZONE Europe/Berlin
ENV TZ Europe/Berlin
#
#RUN yum update && yum install -my \
#        tzdata \
#        mc \
#        htop \
#        && rm /etc/localtime \
#        && ln -snf /usr/share/zoneinfo/$TIMEZONE /etc/localtime \
#        && dpkg-reconfigure -f noninteractive tzdata \
#        && yum clean
