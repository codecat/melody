# melody

> :notes: Minimalist websocket framework for Go.

Melody is websocket framework based on [github.com/fasthttp/websocket](https://github.com/fasthttp/websocket)
that abstracts away the tedious parts of handling websockets. It gets out of
your way so you can write real-time apps. Features include:

* [x] Clear and easy interface similar to `net/http` or Gin.
* [x] A simple way to broadcast to all or selected connected sessions.
* [x] Message buffers making concurrent writing safe.
* [x] Automatic handling of sending ping/pong heartbeats that timeout broken sessions.
* [x] Store data on sessions.

## Full readme
This is a fork that adds support for fasthttp.

Please refer to [the original project](https://github.com/olahol/melody) for more details.
