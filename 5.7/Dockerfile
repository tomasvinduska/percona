################################################################################
# Base image
################################################################################

FROM percona:5.7

# Environments
ENV TIMEZONE Europe/Berlin

RUN apt-get update && apt-get install -my \
        tzdata \
        mc \
        htop \
        && rm /etc/localtime \
        && ln -snf /usr/share/zoneinfo/$TIMEZONE /etc/localtime \
        && dpkg-reconfigure -f noninteractive tzdata \
        && apt-get clean
