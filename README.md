# mackerel-plugin-aws-step-function
AWS Step Functions custom metrics plugin.

[![Build Status](https://travis-ci.org/mackerelio/mackerel-plugin-aws-step-functions.svg?branch=master)][travis]

[travis]: https://travis-ci.org/mackerelio/mackerel-plugin-aws-step-functions

## Synopsis

```shell
mackerel-plugin-aws-step-functions [-access-key-id=<id>] [-secret-access-key=<key>] [-region=<region>] [-state-machine-arn=<arn>] [-metric-key-prefix=<prefix>]
```

## Example of mackerel-agent.conf

```
[plugin.metrics.aws-step-functions]
command = "/path/to/mackerel-plugin-aws-step-functions"
```
