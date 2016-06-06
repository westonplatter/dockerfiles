FROM ruby:2.3.1

# ruby, pg dependencies
RUN apt-get update -qq \
  && apt-get install -y \
    build-essential \
    libpq-dev \
    ruby-dev \
    zlib1g-dev \
    liblzma-dev \
    libxslt-dev \
    libxml2-dev \
    locales

# nodejs dependencies
RUN apt-get install -y \
    nodejs \
