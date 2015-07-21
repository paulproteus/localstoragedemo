## Purpose of this repo

Find out if `localStorage` is supported for web apps running on hosts that are
part of the public suffix list.

Rationale: https://groups.google.com/forum/#!topic/sandstorm-dev/yxx6invce2w

## Steps to set up

1. Add a line to `/etc/hosts/` like `127.0.0.1	localhost com` so that you can access this over http://com/.
2. `python -m SimpleHTTPServer`
3. Visit http://com:8000/

## License

This README is Apache License 2.0.

Contents of this repo are (C) Sandstorm Development Group, Inc.

index.html is copied from
http://people.w3.org/mike/localstorage.html , apologies to Mike; if you
want this removed, let me know.


