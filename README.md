# ViON - RPC

Part of the ViON video surveillance platform ([vionvision.tech](https://vionvision.tech)).

Based on [camera.ui rpc](https://github.com/cameraui/rpc) by seydx (MIT), used with the author's permission.
Package names (`@camera.ui/*`, `camera-ui-*`) and Go module paths are kept for compatibility.
To pull upstream changes: `git remote add upstream https://github.com/cameraui/rpc.git && git fetch upstream && git merge upstream/main`.

[![npm](https://img.shields.io/npm/v/@camera.ui/rpc?label=npm&logo=npm)](https://www.npmjs.com/package/@camera.ui/rpc)
[![PyPI](https://img.shields.io/pypi/v/camera-ui-rpc?label=pypi&logo=pypi&logoColor=white)](https://pypi.org/project/camera-ui-rpc/)
[![Go](https://img.shields.io/github/v/tag/cameraui/rpc?filter=go/*&label=go&logo=go&logoColor=white)](https://pkg.go.dev/github.com/cameraui/rpc/go)

A lightweight, NATS-based RPC framework powering communication across the ViON ecosystem. Supports request/response, streaming, bidirectional channels and callbacks.

Available for three runtimes:

| Runtime | Package                               |
| ------- | ------------------------------------- |
| Node    | `@camera.ui/rpc` (`./node`)           |
| Go      | `github.com/cameraui/rpc/go` (`./go`) |
| Python  | `camera-ui-rpc` (`./python`)          |

---

_Part of the ViON ecosystem._
