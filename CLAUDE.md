# HyperLab Project

## Git & GitHub Sync

**Remote:** https://github.com/yinshuo-thu/HyperLab.git (HTTPS)

**Important:** This machine uses a corporate VPN (`vpn3.mhfunds.com`) that blocks GitHub SSH (port 22) by hijacking DNS. Always use HTTPS remote URL, not SSH.

### After every code change, commit and push:
```bash
git add -A
git commit -m "描述本次修改"
git push origin master
```

If push fails with authentication error, generate a GitHub Personal Access Token:
- GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
- Scopes: `repo`
- Use token as password when prompted

If push fails with network error, disconnect from VPN first, then push.
