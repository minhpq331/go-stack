# Go Stack

Dockerfile for golang stack

## Requirements

- `go.sum`
- `go.mod`
- Runtime store in `cmd/server/*.go`

## Example Dockerfile

```Dockerfile
FROM minhpq331/go-stack:alpine-builder AS builder

FROM minhpq331/go-stack:alpine-runtime
```

