FROM ruby:2.3.0

# ruby, nodejs, pg dependencies
RUN apt-get update -qq \
  && apt-get install -y \
    build-essential \
    libpq-dev \
    ruby-dev \
    zlib1g-dev \
    liblzma-dev \
    libxslt-dev \
    libxml2-dev \
    nodejs \
    locales

# heroku toolbelt install
RUN curl https://toolbelt.heroku.com/install.sh | sh
ENV PATH $PATH:/usr/local/heroku/bin

