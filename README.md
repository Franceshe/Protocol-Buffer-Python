# Protocol-Buffer-Python
* gRPC provides protocol buffer compiler plugins that generate client- 
and server-side code.


## gprc
### gprc defines 4 kind of services:
* 1. Unary rpcs with single request form client and single response from server.
* 2. Client reads a stream of reponse from server
* 3. Client sends a stream of greetings to server and wait for response.
* 4. Bidirectional read and wirte for both client and server.


### Advantage:
* Selective message compression. eg: mixed image and text
* First class load balancing.
* Heavily optimized. gRPC (the library) is under continuous benchmarks

### Performance 
* gRPC is roughly 7 times faster than REST when receiving data & 
roughly 10 times faster than REST when sending data for this specific
payload. This is mainly due to the tight packing of the Protocol 
Buffers and the use of HTTP/2 by gRPC

### Jargon
* Interface Definition Language (IDL) 

## Reference:
* [grpc](https://grpc.io/docs/what-is-grpc/introduction/)
* [Evaluating performance of REST vs gRPC](https://medium.com/@EmperorRXF/evaluating-performance-of-rest-vs-grpc-1b8bdf0b22da)
* [Is gRPC(HTTP/2) faster than REST with HTTP/2?](https://stackoverflow.com/questions/44877606/is-grpchttp-2-faster-than-rest-with-http-2)
