# SimplemdeRails

[Simplemde markdown editor](https://github.com/NextStepWebs/simplemde-markdown-editor) v. 1.11.2. for RoR.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'simplemde_rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install simplemde_rails

## Usage

Add in application.css

```sass
@import 'simplemde/simplemde.min'
```

Add in application.js

```coffee
#= require 'simplemde/simplemde.min'
```

Use it like [here](https://github.com/NextStepWebs/simplemde-markdown-editor). Docs and more info is placed [here](https://github.com/NextStepWebs/simplemde-markdown-editor#configuration).

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/red-rocks/simplemde_rails.
