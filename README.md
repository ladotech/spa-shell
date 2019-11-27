# Spring Boot Application Shell

Shell script for management of Spring Boot Application.

## Usage

### Install

```shell
cd /path/to/your/app
## `ls` will be:
## - your-app.jar
## - application.properties

## use newest
wget https://gitlab.com/ladotech/spa-shell/raw/master/spa
chmod +x spa
```

You can edit it with `vi spa` to change something.

### Start

Start app if it is not running.

```shell
./spa your-app.jar start
```

### Stop

Stop app if it is running.

```shell
./spa your-app.jar stop
```

### Restart

This operation will stop app first, if the app is running. Otherwise, just same as `start` command.

```shell
./spa your-app.jar restart
```

### Status

Show if the app is running.

```shell
./spa your-app.jar status
```

### Rolling

Rolling logs file `logs/console.log` and `logs/error.log` by time. This operation will be also executed when the app starts, but you can run it with `rolling` command at anytime you want.

```shell
./spa your-app.jar rolling
```
