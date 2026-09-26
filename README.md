# ViON - RPC

Part of the ViON video surveillance platform ([vionvision.tech](https://vionvision.tech)).

Based on [camera.ui rpc](https://github.com/cameraui/rpc) by seydx (MIT), used with the author's permission.
npm packages are published under the `@vionvision` scope (`@vionvision/rpc`); Python packages and Go module paths keep their upstream names.
To pull upstream changes: `git remote add upstream https://github.com/cameraui/rpc.git && git fetch upstream && git merge upstream/main`.

[![npm](https://img.shields.io/npm/v/@vionvision/rpc?label=npm&logo=npm)](https://www.npmjs.com/package/@vionvision/rpc)
[![PyPI](https://img.shields.io/pypi/v/camera-ui-rpc?label=pypi&logo=pypi&logoColor=white)](https://pypi.org/project/camera-ui-rpc/)
[![Go](https://img.shields.io/github/v/tag/cameraui/rpc?filter=go/*&label=go&logo=go&logoColor=white)](https://pkg.go.dev/github.com/cameraui/rpc/go)

A lightweight, NATS-based RPC framework powering communication across the ViON ecosystem. Supports request/response, streaming, bidirectional channels and callbacks.

Available for three runtimes:

| Runtime | Package                               |
| ------- | ------------------------------------- |
| Node    | `@vionvision/rpc` (`./node`)           |
| Go      | `github.com/cameraui/rpc/go` (`./go`) |
| Python  | `camera-ui-rpc` (`./python`)          |

---

_Part of the ViON ecosystem._
