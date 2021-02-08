# IpList
Short description and motivation.

## Usage
How to use my plugin.

## Installation
Add this line to your application's Gemfile:

```ruby
gem 'ip_list'
```

And then execute:
```bash
$ bundle
```

Or install it yourself as:
```bash
$ gem install ip_list
```

## Testing

1. Create your database.yml in spec/internal/config directory
2. Create these folders assets/config and this file manifest.js in the spec/internal/app directory if they do not exist

## Test database setup
```
# EXAMPLE
  test:
  adapter: postgresql
  host: localhost
  database: rails_hq_ip_whitelist
  username: postgres
  password:
  timeout: 5000
  encoding: utf8
  pool: 5
 ```

## Running Test

whole suite

1. bundle exec rspec spec

Single

2. bundle exec rspec --backtrace spec/PATH_TO_FILE.rb Note: --backtrace for full error stack

Extra tips

1. bundle exec irb to use your local ruby version
2. bundle exec ruby PATH_TO_FILE.rb to run a single ruby file with the ruby version for the app


## Linting

You must make sure the code is properly linted. Achieve that by running the line below

`bundle exec rubocop
`

1. Update the .rubocop-https---onehq-com-rubocop-yml file if any modifications are required.
2. Make sure to update `TargetRubyVersion` in the file for any ruby version upgrade.

## Contributing
Contribution directions go here.

## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
