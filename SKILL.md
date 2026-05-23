---
name: ifconfig
slug: ifconfig
version: 1.0.0
description: Let your AI agent debug your server's external requests  (no API key required).
homepage: https://ifconfig.me/
author: ibnaleem
repository: https://github.com/ibnaleem/ifconfig-skill
license: GPL-3.0
changelog: "Initial release"
metadata: {"openclaw":{"requires":{"bins":["curl"]},"os":["linux","darwin","win32"]}}
---

## ifconfig

One primary service, no API keys needed.

Get IP address of your server:

```bash
curl ifconfig.me
```

Get User-Agent:

```bash
curl ifconfig.me/ua
```

Get lang/language:

```bash
curl ifconfig.me/lang
```

Get encoding:

```bash
curl ifconfig.me/encoding
```

Get mime:

```bash
curl ifconfig.me/mime
```

Get charset:

```bash
curl ifconfig.me/charset
```

Get forwarded IPs:

```bash
curl ifconfig.me/forwarded
```

Get all headers (text/plain):

```bash
curl ifconfig.me/all
```

Get all headers (json):

```bash
curl ifconfig.me/all.json
```