# Protocol::HTTP2 example with nghttp2

[Protocol::HTTP2](https://github.com/vlet/p5-Protocol-HTTP2) (HTTP/2 library for Perl) example with [nghttp2](https://github.com/tatsuhiro-t/nghttp2) server (nghttpd).

## Setup

``` console
$ carton install
```

## Run example

- Server

``` console
$ nghttpd --no-tls -v 8080
```

- Client

``` console
$ carton exec -- perl client-simple.pl
$ carton exec -- perl client-multi-streams.pl
```
