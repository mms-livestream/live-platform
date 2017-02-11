FROM ruby:2.1.10-slim

RUN apt-get update && apt-get install -y ruby ruby1.8-dev build-essential wget libruby1.8 rubygems
RUN gem update --no-rdoc --no-ri
RUN gem install ohai chef --no-rdoc --no-ri

