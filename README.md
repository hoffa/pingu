![](https://i.imgur.com/NrJhFn0.png)

# pingu

[![Build Status](https://travis-ci.org/hoffa/pingu.svg?branch=master)](https://travis-ci.org/hoffa/pingu)

`pingu` lets you know when your long-running process finishes.

Will run on pretty much any POSIX system.

## Example

```Shell
pingu make
```

## Installation

```Shell
curl -Lo /usr/local/bin/pingu https://raw.githubusercontent.com/hoffa/pingu/master/pingu
chmod +x /usr/local/bin/pingu
```

You'll also need to create an [Incoming Webhook](https://api.slack.com/incoming-webhooks) and pass the URL to `pingu` using the `SLACK_WEBHOOK_URL` environment variable.
