![Screenshot](https://i.imgur.com/PEfFS0M.png)

# 🐧 pingu

I often work on the go through SSH, and like to know when my processes finish. `pingu` helps with that.

## Example

```
pingu docker build -t windows-xp .
```

## Install

```
cd /usr/local/bin
curl -O https://raw.githubusercontent.com/hoffa/pingu/master/pingu
chmod +x pingu
```

## Configuration

Create a `.pingurc` file in your home directory similar to this (replace with correct values):

```
channel=@U1234ABCD
webhook=https://hooks.slack.com/services/T02E4V78N/B2ALJAABC/aBcdEFgHi123456789lMnQLi
```

If it doesn't make much sense, here's [how to create an incoming webhook](https://api.slack.com/incoming-webhooks#getting-started) and [how to find your Slack ID](https://api.slack.com/changelog/2017-09-the-one-about-usernames#mapping).
