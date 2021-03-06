# Buff

Buff is a Buffer API Wrapper written in Ruby.  It provides more thorough API coverage than the existing gem.

Since the gem is currently in ALPHA development, the interface is prone to change.  Please wait until v0.1.0 is released to become reliant on interface.

## Installation

[![Coverage Status](https://coveralls.io/repos/zph/buff/badge.png?branch=master)](https://coveralls.io/r/zph/buff?branch=master)

Once Buff is released as a gem, the following instructions will work. For now please `git clone` the repo.

#### Note: Fixtures are not currently public. They will be uploaded after sensitive info is sanitized.

Add this line to your application's Gemfile:

    gem 'buff', :git => 'zph/buff'

And then execute:

    $ bundle

Once gem is pushed to RubyGems:
> Or install it yourself as:

>     $ gem install buff

## Usage

  * Note which API coverage exists and have fun!
  * Authentication is not included in this gem (Try OAuth-buffer)

## API Coverage

#### Implemented

* User
* Profiles (:get)
* Updates (:get)
* Updates (:post, #create_update, #change_update_text, #destroy_update, #share_update, #shuffle_updates, #reorder_updates)
* Links
* Info
* Error Codes

#### Not Implemented

* Profiles (:post, #set_schedules)
* Caching

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Issues, advice and refactoring is welcome.

Also, this project is newcomer friendly!! We'd love to be your first Open Source Software contribution and would be happy to assist in that process.

Reach out on Twitter [@_ZPH](http://twitter.com/_ZPH).
