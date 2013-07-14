# ink2-rails
Forked from https://github.com/npestana/ink-rails

Ink version 2.x.x for Rails Asset Pipeline.

## Installation

Add this line to your application's Gemfile:

    gem 'ink2-rails', github: 'mutablestate/ink2-rails'

And this line for FontAwesome support:

    gem 'font-awesome-rails'

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install ink2-rails

## Usage

Add this lines to your application.css before "*= require_tree .":

	*= require ink
    *= require font-awesome

Add these lines to your application.js before "//= require_tree .":

    //= require ink.min
    //= require ink.ui.min
    //= require autoload
    //= require html5shiv


More information about Ink Framework at https://github.com/sapo/Ink.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
