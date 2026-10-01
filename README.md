# 🐘 bashraccoon - Mastodon + Blog

Mein eigener Mastodon-Server mit integriertem Blog.

- **Mastodon:** https://bashraccoon.de/@admin
- **Blog:** https://bashraccoon.de/blog

## 🚀 Architektur

- Podman (rootless)
- PostgreSQL + Redis
- NGINX + SSL
- Zola (Blog Generator)
- GitHub Actions (Auto-Deploy)

## 📝 Blog schreiben

Neue Posts in `blog/content/posts/*.md` - Auto-Deploy via GitHub Actions!

## 🔒 Sicherheit

Dieses Repo ist PUBLIC für Blog-Posts. Secrets sind:
- In GitHub Secrets gespeichert
- In `.env.local` (gitignore!)
- NIEMALS im Repo

---

**Autor:** schmid-di  
**Lizenz:** MIT
