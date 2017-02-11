FROM ruby:2.3.3-slim

RUN apt-get update && apt-get install -y build-essential wget rubygems
RUN gem update --no-rdoc --no-ri
RUN gem install ohai chef --no-rdoc --no-ri

