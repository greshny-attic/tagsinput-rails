# tagsinput-rails

tagsinput-rails wraps the [jQuery-Tags-Input](http://xoxco.com/projects/code/tagsinput/) plugin in a rails engine for simple
use with the asset pipeline provided by rails 3.1. The gem includes the development (non-minified)
source for ease of exploration. The asset pipeline will minify in production.

## Installation

Add this line to your application's Gemfile:

    gem 'tagsinput-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install tagsinput-rails

## Usage

Add the following directive to your Javascript manifest file (application.js):

    //= require jquery.tagsinput

Add to your app/assets/stylesheets/application.css

    *= require jquery.tagsinput

## Versioning

tagsinput-rails 1.3.3.1 == jQuery-Tags-Input 1.3.3

Every attempt is made to mirror the currently shipping jQuery-Tags-Input version number wherever possible.
The major, minor, and patch version numbers will always represent the jQuery-Tags-Input version. Should a gem
bug be discovered, a 4th version identifier will be added and incremented.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
