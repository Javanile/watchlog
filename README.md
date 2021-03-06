# watch-log 

Watch your log files during development and save your time.

[![Build Status](https://travis-ci.org/javanile-bot/watch-log.svg?branch=master)](https://travis-ci.org/javanile-bot/watch-log)
[![Code Climate](https://codeclimate.com/github/javanile-bot/watch-log/badges/gpa.svg)](https://codeclimate.com/github/javanile-bot/watch-log)
[![Test Coverage](https://codeclimate.com/github/javanile-bot/watch-log/badges/coverage.svg)](https://codeclimate.com/github/javanile-bot/watch-log/coverage)

## usage

**STEP 1** - Install global 'watch-log' tool

```bash
$ npm install watch-log -g
```

**STEP 2** - Create a file ".debug.yml" into your project with relatives path of log files to get under the watcher activity

```yml
## file: .debug.yml
watch-log:
  files:
    - logs/error.log 
    - logs/debug.log 
```

**STEP 3** - Simply run watch-log on your folder project on bash console
```bash
$ watch-log
```

**STEP 4** - When a log file changes output are ready for your debug.
