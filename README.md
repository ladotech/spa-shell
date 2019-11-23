# Spring Boot Application Shell
Shell script for management of Spring Boot Application

## Usage

### Install

```shell
cd /path/to/your/app
# `ls` will be:
# - your-app.jar
# - application.properties
wget https://github.com/ladotech/spa-shell/releases/download/0.1/spa
chmod +x spa
```

### Start

```shell
./spa your-app.jar start
```

### Stop

```shell
./spa your-app.jar stop
```

### Restart

```shell
./spa your-app.jar restart
```

### Status

```shell
./spa your-app.jar status
```

### Rolling

```shell
./spa your-app.jar rolling
```
