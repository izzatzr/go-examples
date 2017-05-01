# Go examples

[![Build Status](https://travis-ci.org/feiskyer/go-examples.svg?branch=master)](https://travis-ci.org/feiskyer/go-examples) [![Go Report Card](https://goreportcard.com/badge/github.com/feiskyer/go-examples)](https://goreportcard.com/report/github.com/feiskyer/go-examples)

Various go examples based on [gobyexample](https://github.com/mmcgrana/gobyexample) with extensions.

- Go basic
- gRPC
- Hyper
- Libvirt client
- Kubernetes
- Networking
- OpenStack client
- And so on

## Golang install

```sh
curl -sL https://storage.googleapis.com/golang/go1.8.1.linux-amd64.tar.gz | tar -C /usr/local -zxf -
export GOPATH='/go'
export PATH=$GOPATH/bin:/usr/local/go/bin/:$PATH
```

## Useful tools

* godep: `go get github.com/tools/godep`
* dep: `go get -u github.com/golang/dep/...`
* govendor: `go get -u github.com/kardianos/govendor`
* gometalinter: `go get -u github.com/alecthomas/gometalinter && gometalinter --install`

