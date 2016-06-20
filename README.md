# Command line tools

## `pg_slack` 🚥

Command line tool to send a message to Slack.

* `PG_SLACK_HOOK` must be set as an environment variable with the Slack hook URL (`https://hooks.slack.com/services/XXXXXXXXX/XXXXXXXXX/XXXXXXXXXXXXXXXXXXXXXXXX`).

```
Usage: pg_slack message [options]
    -c, --channel channel            Channel
    -u, --username username          Username
        --icon-emoji emoji           Icon emoji
        --icon-url url               Icon URL
    -m, --mrkdwn                     Format as markdown
    -h, --help                       Displays Help
```
