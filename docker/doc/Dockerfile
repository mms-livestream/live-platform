FROM alpine

RUN apk update && apk upgrade && apk --update add \
    ruby ruby-irb ruby-rake ruby-io-console ruby-bigdecimal ruby-json ruby-bundler \
    libstdc++ tzdata bash ca-certificates \
    git \
    &&  echo 'gem: --no-document' > /etc/gemrc

RUN git clone https://github.com/rstoke/live-doc.git

EXPOSE 4567
