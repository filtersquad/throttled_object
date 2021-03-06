# throttled_object

`throttled_object` is a Ruby 1.9 library built on top of ruby to provide throttled access
to a given object. It provides an interface to interact with an object, either sleeping or raising
an exception when it's not available.

The ideal use for this is for access to APIs with a blocking interface (e.g. Run the code in a thread,
sleep until it's available).

**PLEASE NOTE:** I don't yet consider this production worthy. There are still bugs in the locking algorithm
that need to be worked out for it work efficiently. This will be done in the near future.

## Installation

Add this line to your application's Gemfile:

    gem 'throttled_object'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install throttled_object

## Usage

TODO: Add here.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

throttled_object is released under the MIT License (see the [license file](https://github.com/filtersquad/throttled_object/blob/master/LICENSE)) and is copyright Filter Squad, 2012.