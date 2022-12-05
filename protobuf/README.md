# Protobuf

Provides use of the protoc command line tool via docker. See https://developers.google.com/protocol-buffers to learn more about Protobuf.

## Usage

This image is hosted [here](https://hub.docker.com/r/aedenj/protobuf)

```
docker run --rm -v `pwd`/protobuf/:/protobuf -v `pwd`/generated/:/generated aedenj/protobuf:3.21.3 /protobuf/[YOUR_PROTO_FILE].proto --java_out=/generated/ --proto_path=/protobuf/
```


