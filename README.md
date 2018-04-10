# stail

## Usage

```sh
curl -sSL finagin.github.io/stail | sh -- -s <server> -p <path_to_dir_containing_storage> [-g <tracing>]
```
e.g.
```sh
curl -sSL finagin.github.io/stail | sh -- -s fozzy -p /var/www/finagin -g local.ERROR
```
