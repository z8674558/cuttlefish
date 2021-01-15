# Cuttlefish

Cuttlefish is a library for Erlang applications that wish to walk the
fine line between Erlang `app.config`s and a sysctl-like syntax.
The name is a pun on the pronunciation of 'sysctl' and jokes are
better explained.

In this fork, parsing function is `hocon:load` instead of `conf_parse:file`
from neotoma. Also, we use `hocon:duration` as a duration conversion function.

## What's it look like to Erlang Developers?

You can learn more about the technical implementation of schemas at:
https://github.com/basho/cuttlefish/wiki/Cuttlefish-for-Erlang-Developers

## Current Status

Cuttlefish is ready for production deployments.
