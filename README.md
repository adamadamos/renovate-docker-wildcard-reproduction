# 30320

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate replaces wildcards when updating Dockerfile packages. `v1.*` to `v2.53.0`.

## Expected behavior

Not sure if it is possible but it would be nice to keep the wildcard and go from `v1.*` to `v2.*`.
Played around with custom regex versioning a bit to no avail.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/30320
