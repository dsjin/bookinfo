FROM ruby:2
WORKDIR /usr/src/app/
COPY . /usr/src/app/
RUN bundle install
EXPOSE 9081
CMD ["ruby", "/usr/src/app/details.rb", "9081"]