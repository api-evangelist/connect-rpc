# Connect-RPC (connect-rpc)

Connect is a slim framework for building browser-friendly and gRPC-compatible HTTP APIs from Protocol Buffer schemas. Servers built with Connect speak the Connect protocol, gRPC, and gRPC-Web simultaneously, while clients can switch between protocols without changing code. Connect provides type-safe SDKs for Go, TypeScript/JavaScript, Swift, Kotlin, and Python, plus the Buf-generated `protoc-gen-connect-*` code generators. The project is open source under the Apache 2.0 license and is maintained by Buf.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/connect-rpc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Open Source
- **Classification:** Open Source

## Tags

- Apache 2.0, Buf, Code Generation, Connect Protocol, gRPC, gRPC-Web, HTTP, Open Source, Protocol Buffers, RPC, SDKs

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-28

## APIs

### connect-go

The Go implementation of Connect. Provides server handlers and clients that speak the Connect, gRPC, and gRPC-Web protocols simultaneously. Generated from .proto files via the protoc-gen-connect-go plugin.

**Human URL:** [https://connectrpc.com/docs/go/](https://connectrpc.com/docs/go/)

#### Tags

- Go, SDK

#### Properties

- [Documentation](https://connectrpc.com/docs/go/)
- [Getting Started](https://connectrpc.com/docs/go/getting-started)
- [GitHub](https://github.com/connectrpc/connect-go)
- [Tutorial](https://connectrpc.com/docs/go/tutorial)

#### Features

- Connect Protocol Server and Client
- gRPC Compatibility
- gRPC-Web Compatibility
- Streaming RPCs
- Interceptors
- Idiomatic net/http Integration

#### Use Cases

- Build a Go service callable from browsers and gRPC clients
- Migrate gRPC services to Connect without breaking clients
- Add HTTP/JSON access to existing Protobuf services

### connect-es (Connect for ECMAScript)

Connect for ECMAScript provides type-safe browser and Node.js clients and Node.js servers from Protobuf schemas.

**Human URL:** [https://connectrpc.com/docs/web/](https://connectrpc.com/docs/web/)

#### Tags

- JavaScript, SDK, TypeScript

#### Properties

- [Documentation](https://connectrpc.com/docs/web/)
- [Getting Started](https://connectrpc.com/docs/web/getting-started)
- [GitHub](https://github.com/connectrpc/connect-es)

#### Features

- Browser Clients
- Node.js Clients
- Node.js Servers
- Tree-Shakable Bundles
- Type-Safe TypeScript
- gRPC-Web Compatibility

#### Use Cases

- Call Protobuf services from React, Vue, or vanilla JS
- Build Node.js servers without a gRPC dependency
- Share TypeScript types between client and server

### connect-swift

Type-safe Connect, gRPC, and gRPC-Web clients for iOS, macOS, watchOS, and tvOS apps.

**Human URL:** [https://connectrpc.com/docs/swift/](https://connectrpc.com/docs/swift/)

#### Tags

- iOS, SDK, Swift

#### Properties

- [Documentation](https://connectrpc.com/docs/swift/)
- [Getting Started](https://connectrpc.com/docs/swift/getting-started)
- [GitHub](https://github.com/connectrpc/connect-swift)

#### Features

- URLSession Integration
- Streaming Support
- gRPC and gRPC-Web Clients
- Async/Await API

#### Use Cases

- Call Protobuf services from iOS apps
- Add streaming RPC to Apple platform clients

### connect-kotlin

Type-safe Connect clients for Android and JVM applications.

**Human URL:** [https://connectrpc.com/docs/kotlin/](https://connectrpc.com/docs/kotlin/)

#### Tags

- Android, JVM, Kotlin, SDK

#### Properties

- [Documentation](https://connectrpc.com/docs/kotlin/)
- [Getting Started](https://connectrpc.com/docs/kotlin/getting-started)
- [GitHub](https://github.com/connectrpc/connect-kotlin)

#### Features

- Coroutines API
- OkHttp Transport
- Streaming Support
- Multi-Protocol Client

#### Use Cases

- Call Protobuf services from Android apps
- Share Kotlin types across mobile and backend

### connect-python

Connect protocol and gRPC clients for Python (beta).

**Human URL:** [https://connectrpc.com/docs/python/](https://connectrpc.com/docs/python/)

#### Tags

- Python, SDK

#### Properties

- [Documentation](https://connectrpc.com/docs/python/)
- [GitHub](https://github.com/connectrpc/connect-python)

#### Features

- ASGI Integration
- Type-Safe Stubs
- Connect and gRPC Clients

#### Use Cases

- Add Protobuf RPC to Python services
- Call Connect services from data-science notebooks

## Common Properties

- [Website](https://connectrpc.com)
- [Documentation](https://connectrpc.com/docs/introduction)
- [GitHub Organization](https://github.com/connectrpc)
- [Demo](https://connectrpc.com/demo)
- [Blog](https://buf.build/blog)
- [Maintainer](https://buf.build)
- [License](https://github.com/connectrpc/connect-go/blob/main/LICENSE)
- [Slack](https://buf.build/links/slack)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
