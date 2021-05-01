# pingu

pingu sends you a Slack message when your process finishes.

Works on any POSIX system with `curl`.

## Installation

```shell
curl -LO https://raw.githubusercontent.com/hoffa/pingu/master/pingu
chmod +x pingu
```

## Usage

```shell
pingu <command>
```

`SLACK_WEBHOOK_URL` must be set.

See the [Slack docs](https://api.slack.com/incoming-webhooks) on how to create a webhook URL.
