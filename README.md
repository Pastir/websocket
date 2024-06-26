# Fasthttp WebSocket

WebSocket is a [Go](http://golang.org/) implementation of the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) for [fasthttp](https://github.com/valyala/fasthttp).

![Gorilla Logo](https://github.com/gorilla/.github/assets/53367916/d92caabf-98e0-473e-bfbf-ab554ba435e5)

_This project is a fork of the latest version of [gorilla/websocket](https://github.com/gorilla/websocket) that continues its development independently._

### Documentation

* [Chat example](_examples/chat)
* [Command example](_examples/command)
* [Client and server example](_examples/echo)
* [File watch example](_examples/filewatch)
* [Write buffer pool example](_examples/bufferpool)

### Status

The WebSocket package provides a complete and tested implementation of
the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. The
package API is stable.

### Installation

```
go get github.com/Pastir/websocket
```
But beware that this will fetch the **latest commit of the master branch** which is never purposely broken, but usually not considered stable anyway.

### Protocol Compliance

The WebSocket package passes the server tests in the [Autobahn Test
Suite](https://github.com/crossbario/autobahn-testsuite) using the application in the [_examples/autobahn
subdirectory](_examples/autobahn).
