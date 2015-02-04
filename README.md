# lita-pagerduty-oncall

PagerDuty (http://pagerduty.com) handler for checking who's on call.

## Installation

Add lita-pagerduty-oncall to your Lita instance's Gemfile:

``` ruby
gem "lita-pagerduty-oncall"
```

## Configuration

Add the following variables to your Lita config file:

``` ruby
config.handlers.pagerduty-oncall.api_key   = ''
config.handlers.pagerduty-oncall.subdomain = ''
```

## Usage

```
@BotName oncall
```

Exmaple:

```
Testing:
  1: Paul Paulison (static)

Chef Client Goalie:
  1: Bob Smith (02/02/15 08:00 - 02/09/15 08:00 UTC)

IT Support:
  -- Empty Rotation --

Operations:
  1: Josh Johnson (02/02/15 17:00 - 02/09/15 17:00 UTC)
  2: Ian Iradium (02/02/15 16:00 - 02/09/15 16:00 UTC)
  3: Stephen Summers (02/03/15 02:00 - 02/06/15 02:00 UTC)
```

## License

[MIT](http://opensource.org/licenses/MIT)
