# Longbridge Binary Protocol

Longbridge Binary Protocol is using for OpenAPI Socket Connection.

[More details](https://open.longbridgeapp.com/docs/socket/protocol/overview)


For `Python` and `C++` user, we provide:
- [Python SDK](https://github.com/longbridgeapp/openapi-python)
- [C++ SDK](https://github.com/longbridgeapp/openapi-cpp)

This repo want to show how to implement Longbridge Binary Protocol.

If you are `Gopher`, you can use the golang implementation to connect our socket gateway.

## Golang Implementation

Check code [here](https://github.com/longbridgeapp/openapi-protocol/tree/main/go).

code structure:

- go - protocol definations
- go/client - client sample code
- go/v1 - protocol version 1 implement
- go/v2 - protocol version 2 implement, not support yet

Example is [here](https://github.com/longbridgeapp/openapi-protocol/tree/main/examples/go)

