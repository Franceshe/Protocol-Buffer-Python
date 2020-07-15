# Protocol-Buffer-Python



## gprc
### Advantage:
* Selective message compression. eg: mixed image and text
* First class load balancing.
* Heavily optimized. gRPC (the library) is under continuous benchmarks
### Performance 
* gRPC is roughly 7 times faster than REST when receiving data & 
roughly 10 times faster than REST when sending data for this specific
payload. This is mainly due to the tight packing of the Protocol 
Buffers and the use of HTTP/2 by gRPC

## Reference:
* [grpc](https://grpc.io/docs/what-is-grpc/introduction/)
* [Evaluating performance of REST vs gRPC](https://medium.com/@EmperorRXF/evaluating-performance-of-rest-vs-grpc-1b8bdf0b22da)
* [Is gRPC(HTTP/2) faster than REST with HTTP/2?](https://stackoverflow.com/questions/44877606/is-grpchttp-2-faster-than-rest-with-http-2)
