# moq.dev/moq (Go module)

Auto-generated mirror of the ergonomic Go wrapper for [Media over QUIC](https://github.com/moq-dev/moq).

Source, issues, and pull requests live in [moq-dev/moq](https://github.com/moq-dev/moq); this repo only carries tagged Go module releases.

## Install

```bash
go get moq.dev/moq@latest
```

```go
import "moq.dev/moq"
```

The import path is served by moq.dev, which points the go command back at this
repo, so the module can move without breaking anyone.

Hand-written Go on top of the raw [moq.dev/moq-ffi](https://pkg.go.dev/moq.dev/moq-ffi) bindings, which carry the prebuilt native libraries. `CGO_ENABLED=1` is required (the default on Unix).

See [moq-dev/moq/go/wrapper/README.md](https://github.com/moq-dev/moq/blob/main/go/wrapper/README.md) for usage and the release process.

Licensed under MIT OR Apache-2.0.
