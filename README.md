# moq-go (Go module)

Auto-generated mirror of the ergonomic Go wrapper for [Media over QUIC](https://github.com/moq-dev/moq).

Source, issues, and pull requests live in [moq-dev/moq](https://github.com/moq-dev/moq); this repo only carries tagged Go module releases.

## Install

```bash
go get github.com/moq-dev/moq-go@latest
```

```go
import "github.com/moq-dev/moq-go/moq"
```

Hand-written Go on top of the raw [github.com/moq-dev/moq-go-ffi](https://github.com/moq-dev/moq-go-ffi) bindings, which carry the prebuilt native libraries. `CGO_ENABLED=1` is required (the default on Unix).

See [moq-dev/moq/go/wrapper/README.md](https://github.com/moq-dev/moq/blob/main/go/wrapper/README.md) for usage and the release process.

Licensed under MIT OR Apache-2.0.
