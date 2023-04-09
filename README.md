# Go-Extras WebSocket

[![GoDoc](https://godoc.org/github.com/go-extras/websocket?status.svg)](https://godoc.org/github.com/go-extras/websocket)
[![Build Status](https://github.com/go-extras/websocket/actions/workflows/main.yml/badge.svg)](https://github.com/go-extras/websocket/actions/workflows/main.yml)

Go-Extras WebSocket is a [Go](http://golang.org/) implementation of the
[WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. It is based on
[Gorilla Websocket](https://github.com/gorilla/websocket), which was archived
by its authors in Dec 2022.


### Documentation

* [API Reference](https://pkg.go.dev/github.com/go-extras/websocket?tab=doc)
* [Chat example](https://github.com/go-extras/websocket/tree/master/examples/chat)
* [Command example](https://github.com/go-extras/websocket/tree/master/examples/command)
* [Client and server example](https://github.com/go-extras/websocket/tree/master/examples/echo)
* [File watch example](https://github.com/go-extras/websocket/tree/master/examples/filewatch)

### Status

The Go-Extras WebSocket package provides a complete and tested implementation of
the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. The
package API is stable.

### Installation

    go get github.com/go-extras/websocket

### Protocol Compliance

The Go-Extras WebSocket package passes the server tests in the [Autobahn Test
Suite](https://github.com/crossbario/autobahn-testsuite) using the application in the [examples/autobahn
subdirectory](https://github.com/go-extras/websocket/tree/master/examples/autobahn).

### Contribution
Contributions are welcome! Please feel free to submit any issues or pull requests.

### License
This module is licensed under the BSD-2-Clause License. See the [LICENSE](LICENSE) file for details.
