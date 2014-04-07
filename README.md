# Rubyfmt

Ruby port of gofmt.

## Usage

```bash
$ echo 'def hello(who="world");puts "Hello #{who}";end' | ./bin/rubyfmt
```

Outputs:

```ruby
def hello(who = "world")
  puts "Hello #{who}"
end
```

## Installation

Add this line to your application's Gemfile:

    gem 'rubyfmt'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rubyfmt

## Credits

- seattle.rb - for ruby_parser & ruby2ruby which do _all_ of the heavy-lifting.

## Contributing

See [CONTRIBUTING.md](https://github.com/wojtekmach/rubyfmt/blob/master/CONTRIBUTING.md)
