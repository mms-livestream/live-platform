FROM ruby:2.3.3-slim

RUN apt-get update && apt-get install -y ruby ruby2.3-dev build-essential wget libruby2.3 rubygems
RUN gem update --no-rdoc --no-ri
RUN gem install ohai chef --no-rdoc --no-ri

