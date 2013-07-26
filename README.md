# Leaflet::Fullscreen::Rails

Integrates the [Leaflet Fullscreen] plugin with Rails asset pipeline

## Installation

Add this line to your application's Gemfile:

    gem 'leaflet-fullscreen-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install leaflet-fullscreen-rails

## Usage

Add the following to your `app/assets/javascripts/application.js`:

    //= require leaflet.fullscreen
        
Add the following to your `app/assets/stylesheets/application.css`:    
    
    *= require leaflet.fullscreen
    
Examples can be found at [brunob]

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License
MIT License, full text of license see [here][License]

*Free Software, Fuck Yeah!*

[License]: https://github.com/kendrikat/leaflet-fullscreen-rails/blob/master/LICENSE.txt "LICENSE"
[Leaflet Fullscreen]: https://github.com/brunob/leaflet.fullscreen
[brunob]: https://github.com/brunob/leaflet.fullscreen#how-
