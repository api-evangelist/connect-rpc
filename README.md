# Connect-RPC (connect-rpc)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
