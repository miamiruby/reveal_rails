# jquery-rails

jQuery! For Rails! So great.

This gem provides:

  * [Zurb's Reveal Jquery Modal library](http://github.com/zurb/reveal)

## Installation

Apps generated with Rails 3.1 or later include jquery-rails in the Gemfile by default. So just make a new app:

```sh
rails new myapp
```

If upgrading from an older version of rails, or for rails 3.0 apps,
add the jquery-rails gem to your Gemfile.

```ruby
gem "jquery-rails"
gem "reveal_rails"
```

And run `bundle install`. The rest of the installation depends on
whether the asset pipeline is being used.

### Rails 3.1 or greater (with asset pipeline *enabled*)

The jquery and jquery-ujs files will be added to the asset pipeline and available for you to use. If they're not already in `app/assets/javascripts/application.js` by default, add these lines:

```js
//= require jquery
//= require jquery_ujs
//= require jquery-ui
//= require reveal
```

## Contributing

Feel free to open an issue ticket if you find something that could be improved. A couple notes:

* If it's an issue pertaining to the reveal javascript, please report it to the [reveal project](http://github.com/zurb/reveal).


## Acknowledgements

Copyright (c) 2013[Paul Kruger and Moises Zaragoza](http://miamiruby.org), released under the MIT License.
Also thanks to the [reveal project](http://github.com/zurb/reveal).
