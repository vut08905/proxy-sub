# proxy-sub

v2rayNG subscription (SOCKS5, clean-first) — auto-updated every 15 min.

Subscribe URL (v2rayNG → Subscription group setting → paste URL → Update):

https://raw.githubusercontent.com/vut08905/proxy-sub/main/sub.txt

One-tap import:

v2rayng://install-sub?url=https%3A%2F%2Fraw.githubusercontent.com%2Fvut08905%2Fproxy-sub%2Fmain%2Fsub.txt

## What's inside

`sub.txt` is base64 of one `socks://ip:port#CC-<latency>ms` line per proxy:
SOCKS5 proxies with known latency ≤ 3000 ms, clean (elite/anonymous)
first, capped at 200 nodes. Regenerated from 5 public free-proxy lists
(proxifly, TheSpeedX, monosans, clarketm, proxmint).

## Honest notes

- Free proxies die fast — if one stops working, pick another or tap
  "Update subscription" in v2rayNG for a fresh list.
- "Alive" means the proxy is listed by a source that validates by fetching
  through it (proxifly every 5 min, monosans hourly, proxmint every 30 min).
  No independent live check is done from this server.
- Only for testing / light scraping. Don't log in or pay through a
  stranger's proxy.
