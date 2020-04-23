FROM ruby:2.6.0

WORKDIR /rails
COPY rails .
RUN bundle install
RUN rails db:migrate RAILS_ENV=production
CMD rails s -e production
