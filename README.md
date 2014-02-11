# MegaLotto

MegaLotto is a Ruby gem to help easilly generate lottery drawings.

This is the result of **Build a Ruby Gem** email course teached by [@BrandonHilkert](https://twitter.com/brandonhilkert).
For more info visit [Learn to Build a Ruby Gem](http://brandonhilkert.com/books/build-a-ruby-gem/) the book he is writing.

Thanks to [@BrandonHilkert](https://twitter.com/brandonhilkert)

## Installation

Add this line to your application's Gemfile:

    gem 'mega_lotto'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mega_lotto

## Usage

``` ruby
require "mega_lotto"

MegaLotto::Drawing.draw # => [23, 22, 3, 7, 16]
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
