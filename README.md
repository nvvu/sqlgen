# sqlgen

[![Build Status](https://travis-ci.org/ng-vu/sqlgen.svg?branch=master)](https://travis-ci.org/ng-vu/sqlgen)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/ng-vu/sqlgen)

This package generates SQL methods from model.

## Quick Start

- Clone this repository.
- Make sure you installed and have [go](https://golang.org/), [dep](https://github.com/golang/dep), [goimports](https://golang.org/x/tools/cmd/goimports) in your $PATH.

```bash
cd $GOPATH/src/github.com/ng-vu/sqlgen
docker-compose up -d
dep ensure
go generate ./examples/sample
go test -v ./examples/sample
```

See [examples](https://github.com/ng-vu/sqlgen/blob/master/examples) for usage.

# License

- [MIT License](https://opensource.org/licenses/mit-license.php)
