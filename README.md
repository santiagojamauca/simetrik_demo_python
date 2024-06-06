# gRPC Communication Example
  This project demonstrates a simple example of using the gRPC protocol for communication between two Python applications.

# Prerequisites
- Python 3.x

- grpcio
 ```
  pip install grpcio grpcio-tools
 ```
  
- and grpcio-tools Python packages
  ```
  python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. greeter.proto
  ```

  these commands will create the necesary files:
  greeter_pb2.py : Contains the Python classes for the Protobuf messages.
  greeter_pb2_grpc.py : Contains the Python classes for the gRPC service and client.

## Files we need:
  greeter.proto
  client.py
  server.py
  
## Run
 python server.py
 python client.py

 Greeter client received: Hello, World!

 This is a basic example of using gRPC in Python.


