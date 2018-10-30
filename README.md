# example-ping-service

## Build

```bash
$ prototool format -d *.proto || prototool format -w *.proto
$ protoc --go_out=plugins=grpc:. *.proto
```
