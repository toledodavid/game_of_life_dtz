# GameOfLifeDtz

The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970.

## Installation

```ruby
gem 'game_of_life_dtz'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install game_of_life_dtz

## Usage
You can run the game of life with default values ​​just by typing:

```ruby
require 'game_of_life_dtz'

game = GameOfLifeDtz::GameOfLifeDtz.new
```
Or personalize the board and seconds:

```ruby
require 'game_of_life_dtz'

dimension = 30
seconds = 1
game = GameOfLifeDtz::GameOfLifeDtz.new(dimension, seconds)
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/game_of_life_dtz. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the GameOfLifeDtz project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/game_of_life_dtz/blob/master/CODE_OF_CONDUCT.md).
