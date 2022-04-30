# Setup

1. Have python installed. We suggest using [pyenv](https://github.com/pyenv/pyenv)

1. Create virtualenv.

```sh
$ python -m venv venv
```

2. Active virtualenv.

```sh
source venv/bin/activate
```

3. Install pip-tools.

```sh
$ python -m pip install pip-tools
```

4. Run pip-sync to download dependencies.

```
$ pip-sync
```

# Running locust

1. Run locust command.

```sh
$ locust
```

You should be able to see the following in your terminal.

```sh
.../INFO/locust.main: Starting web interface at http://0.0.0.0:8089 (accepting connections from all network interfaces)
.../INFO/locust.main: Starting Locust 2.8.6
```