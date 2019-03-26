1. defind the function
2. set up protocol buffers
3. generate gRPC classes for python
  ```
  - $ pip install grpcio
  - $ pip install grpcio-tools
  - $ python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. calculator.proto
  ```
4. create a gRPC server
5. create a gRPC client

The client and server will exchange the function with a rpc call.
