# Protobuf plugin failure demo

This repo demonstrates a compiler failure for the roadrunner protobuf plugin used to generate gRPC server interfaces.

## Prerequisites

1. You must have the Roadrunner `protoc-gen-php-grpc` binary in your `$PATH`
2. You should have `buf` installed

## Running locally

```sh
cd protos
buf generate
```

You should see a segmentation fault.
