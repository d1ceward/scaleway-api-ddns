# scaleway-ddns (v0.1.0)
![GitHub Workflow Status (main)](https://github.com/d1ceward/scaleway-ddns/actions/workflows/main.yml/badge.svg?branch=master)
[![Docker Pulls](https://img.shields.io/docker/pulls/d1ceward/scaleway-ddns.svg)](https://hub.docker.com/r/d1ceward/scaleway-ddns)
[![GitHub issues](https://img.shields.io/github/issues/d1ceward/scaleway-ddns)](https://github.com/d1ceward/scaleway-ddns/issues)
[![GitHub license](https://img.shields.io/github/license/d1ceward/scaleway-ddns)](https://github.com/d1ceward/scaleway-ddns/blob/master/LICENSE)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/d1ceward/scaleway-ddns. By contributing you agree to abide by the Code of Merit.

1. Fork it (<https://github.com/d1ceward/scaleway-ddns/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Development building and running

1. Install corresponding version of Crystal lang (cf: `.crystal-version` file)
2. Install Crystal dependencies with `shards install`
3. Build with `shards build`

The newly created binary should be at `bin/scaleway-ddns`

### Running tests

```shell
crystal spec
```

## Contributors

- [d1ceward](https://github.com/d1ceward) - creator and maintainer
