source "https://rubygems.org"

group :development, :test do
  gem 'bigdecimal'
  gem 'geoip'
  gem 'ip2location_ruby'
  gem 'logger'
  gem 'mongoid'
  gem 'ostruct'
  gem 'rails', '~>5.1.0'
  gem 'rake'
  gem 'rubyzip'
  gem 'test-unit' # needed for Ruby >=2.2.0

  platforms :jruby do
    gem 'jgeoip'
    gem 'jruby-openssl'
  end
end

group :test do
  platforms :ruby, :mswin, :mingw do
    gem 'sqlite3'
    gem 'sqlite_ext'
  end

  gem 'mutex_m'
  gem 'webmock'

  platforms :ruby do
    gem 'mysql2', '~> 0.5.4'
    gem 'pg', '~> 1.5.9'
  end

  platforms :jruby do
    gem 'activerecord-jdbcpostgresql-adapter'
    gem 'jdbc-mysql'
    gem 'jdbc-sqlite3'
  end
end

gemspec
