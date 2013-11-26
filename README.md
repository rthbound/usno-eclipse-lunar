# USNO::Eclipse::Lunar

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'usno-eclipse-lunar'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install usno-eclipse-lunar

## Usage

First, `require usno/eclipse/lunar`

```ruby
# e.g.
USNO::Eclipse::Lunar::Data.new(lat: 87, long: 30, date: Time.new(2014, 10, 7)).call.data

#or

USNO::Eclipse::Lunar::Data.new(city: "Gulf Shores, state: "Alabama", date: Time.new(2014, 10, 7), request_class: USNO::Eclipse::Lunar::USRequest).call.data
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
