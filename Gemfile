source 'https://rubygems.org'

gem "sinatra"
gem "sinatra-activerecord"
gem "sinatra-flash"
gem "sinatra-contrib", github: "sinatra/sinatra-contrib"

gem "rake"
gem "delayed_job_active_record"
gem "bcrypt-ruby"

gem "feedzirra", github: "swanson/feedzirra"
gem "loofah"
gem "nokogiri"
gem "feedbag", github: "dwillis/feedbag"

gem "coveralls", require: false

group :production do
  gem "unicorn"
  gem "pg"
end

group :development do
  gem "sqlite3"
end

group(:development, :testing) do
  gem "pry"
  gem "rspec"
  gem "rspec-html-matchers"
  gem "rack-test"
  gem "shotgun"
  gem "racksh"
  gem "faker"
  gem "foreman"
end