# GCRA

This page tracks various projects that are based on
[generic cell rate algorithm][gcra].

## Go

* [throttled][throttled]: An implementation that can be
  used standalone or easily plugged into a Go HTTP stack.

## Redis

* [redis-cell][redis-cell]: An implementation that can be
  loaded from directly within Redis as a module.

## Ruby

* [gcra-ruby][gcra-ruby]: An implementation in Ruby which
  has a data format in Redis which is compatible with
  Throttled.
* [redis-gcra][redis-gcra]: An implementation that runs in
  Lua from within Redis and which provides a Ruby API.


[gcra]: https://en.wikipedia.org/wiki/Generic_cell_rate_algorithm
[gcra-ruby]: https://github.com/Barzahlen/gcra-ruby
[redis-cell]: https://github.com/brandur/redis-cell
[redis-gcra]: https://github.com/rwz/redis-gcra
[throttled]: https://github.com/throttled/throttled
