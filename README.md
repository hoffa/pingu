# :penguin: pingu

[![Build Status](https://travis-ci.org/hoffa/pingu.svg?branch=master)](https://travis-ci.org/hoffa/pingu)

pingu lets you know when your process finishes.

Supports Slack and Chime. Works on any POSIX system with `curl`.

## Usage

```shell
pingu <command>
```

Either `SLACK_WEBHOOK_URL` or `CHIME_WEBHOOK_URL` must be set.

See relevant docs to create webhook URLs:
- [Slack](https://api.slack.com/incoming-webhooks)
- [Chime](https://docs.aws.amazon.com/chime/latest/ug/webhooks.html)

## Example

```shell
pingu docker build -t windows .
```

## Installation

```shell
curl -Lo /usr/local/bin/pingu https://raw.githubusercontent.com/hoffa/pingu/master/pingu
chmod +x /usr/local/bin/pingu
```

You'll need to create an [Incoming Webhook](https://api.slack.com/incoming-webhooks) and pass the URL to pingu using the `SLACK_WEBHOOK_URL` environment variable. Or you can just `export` the variable during shell initialization.
