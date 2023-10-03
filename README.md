<h1 align="center">sing-box</h1>

<p align="center">The universal proxy platform.</p>

<p align="center">
    <a href="https://ghcr.io/4fx/sing-box">Container Registry</a> ·
    <a href="https://github.com/SagerNet/sing-box">Project Source</a> ·
    <a href="https://ghcr.io/akafeng/sing-box">Container Registry original</a>
</p>

<p align="center">
    <img src="https://img.shields.io/github/actions/workflow/status/4fx/docker-sing-box/push.yml?branch=main" />
    <img src="https://img.shields.io/github/last-commit/4fx/docker-sing-box" />
    <img src="https://img.shields.io/github/v/release/4fx/docker-sing-box" />
    <img src="https://img.shields.io/github/release-date/4fx/docker-sing-box" />
</p>

---

### Pull The Image

```bash
$ docker pull ghcr.io/4fx/sing-box
```

### Start Container

```bash
$ docker run -d \
  -v /etc/sing-box/:/etc/sing-box/ \
  --restart=always \
  --name=sing-box \
  ghcr.io/4fx/sing-box \
  -C /etc/sing-box/ run
```
