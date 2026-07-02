# NajaCoder

A **Natural Language Developer Environment (NLDE)** — natural language as the
input layer, code as a navigable graph.

> **This GitHub repository is a binary-distribution channel.** Source code is
> not published here. Every NajaCoder build ships as a release asset — see the
> [Releases page](./releases/latest).

## Downloads

Each release provides pre-built single-file binaries plus matching SHA-256
checksums:

| Asset | Platform |
|-------|----------|
| `najacoder-<version>-darwin-arm64` | macOS · Apple Silicon |
| `najacoder-<version>-darwin-x64`   | macOS · Intel |
| `najacoder-<version>-linux-x64`   | Linux · x86_64 |

Open the [Releases page](./releases/latest), download the binary for your
platform, verify it against its `.sha256`, then run it:

```sh
chmod +x najacoder-<version>-<platform>
./najacoder
```

Verify a download:

```sh
shasum -a 256 -c najacoder-<version>-<platform>.sha256
```

## License

MIT — see [LICENSE](./LICENSE).