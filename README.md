# API Consumer #

Consumes the events beacon calls from kafka queue and stores into cassandra.

[![Build Status](https://travis-ci.org/octoai/apiconsumer.svg?branch=master)](https://travis-ci.org/octoai/apiconsumer)

## Setup ##

- Clone the repo
- `git submodule init`
- Perform `bundle install`

### Start

```
lang=bash
ruby consumer.rb start
```

You can start multiple instances by running the above command multiple times.

### Get Status

```
lang=bash
ruby consumer.rb status
```

### Stop

```
lang=bash
ruby consumer.rb stop
```


### Logs

- Available at `PROJ_DIR/shared/logs/`
- Also check the `logfile` config at `config/config.yml`
