# serverless-plugin-aws-info-json

A [Serverless](https://serverless.com/) plugin that adds JSON and file output options to the
[`info`](https://serverless.com/framework/docs/providers/aws/cli-reference/info/) command.

This is based in its entirety on https://github.com/jkehres/serverless-plugin-info-json and will potentially be
superseded by releases thereof

## Installation

First, install the plugin via npm:

`npm install serverless-plugin-aws-info-json`

Second, edit your `serverless.yml` file and add the following section:

```yaml
plugins:
    - serverless-plugin-aws-info-json
```

## Usage

In addition to the normal command line arguments provided by the `info` command, this plugin allows you to use the
following extra arguments as well:

* `--json` / `-j` Format output as JSON instead of text.
* `--file <FILE>` / `-f <FILE>` Send command output to the specified file instead of stdout.
