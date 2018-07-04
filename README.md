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

Copy [`.pingurc`](.pingurc) to your home directory and edit the values as needed.

If you're not too familiar with this, here's [how to create an incoming webhook](https://api.slack.com/incoming-webhooks#getting-started) and [how to find your Slack ID](https://api.slack.com/changelog/2017-09-the-one-about-usernames#mapping).
