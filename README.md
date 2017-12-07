# Tcp echo server written in Pony

A [Pony](https://ponylang.org) TCP server that receives a
text message from a client over a TCP connection and
sends it back to the client.

# Compile
```
$ cd tcp_echo_server
$ ponyc ../tcp_echo_server
```
# Run
Start server in one terminal window:
```
wink@wink-envy:~/prgs/ponylang/tcp_echo_server (master)
$ ./tcp_echo_server

```
In another terminal window run the client:
```
wink@wink-envy:~/prgs/ponylang/tcp_echo_server (master)
$ ../tcp_echo_client/tcp_echo_client 
GOT:hello world
```

# Acknowledgements
From the [actor TCPListener](https://github.com/ponylang/ponyc/blob/master/packages/net/tcp_listener.pony) documentation in the [ponyc](https://github.com/ponylang/ponyc) repo.
