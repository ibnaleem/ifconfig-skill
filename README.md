# ⚙️ Ifconfig-Skill
Let your AI agent debug your server's external requests

## 🚀 Getting Started
Install through Clawhub (requires Clawhub CLI):
```bash
$ clawhub install ifconfig
```
Alternative install:
```bash
$ openclaw skills install ifconfig
```

## ❓ What Is This?
Sometimes you want the `User-Agent` your agent sends in its `curl` requests. Sometimes you want to know the external IP address of your agent's server. This skill allows your agent to do this for you.

1. Get the external IP address of your agent's server
2. Get the `User-Agent` your agent sends in its `curl` requests
3. Get the `lang` your agent sends in its `curl` requests
4. Get the `encoding` your agent sends in its `curl` requests
5. Get the `mime` your agent sends in its `curl` requests
6. Get the `forwarded` your agent sends in its `curl` requests
7. Get all headers your agent sends in its `curl` requests

## 🛡️ Security
This skill calls an external API. Files are never modified. Nothing on your OS is touched. Nothing that you did not specifically send to the external API is ever sent.

## 📜 References:

https://ifconfig.me/
