# :penguin: pingu

[![Build Status](https://travis-ci.org/hoffa/pingu.svg?branch=master)](https://travis-ci.org/hoffa/pingu)

pingu lets you know when your process finishes.

Works on any POSIX system with `curl`.

## Example

```Shell
pingu make
```

## Installation

```Shell
curl -Lo /usr/local/bin/pingu https://raw.githubusercontent.com/hoffa/pingu/master/pingu
chmod +x /usr/local/bin/pingu
```

You'll need to create an [Incoming Webhook](https://api.slack.com/incoming-webhooks) and pass the URL to pingu using the `SLACK_WEBHOOK_URL` environment variable. Or you can just `export` the variable during shell initialization.
