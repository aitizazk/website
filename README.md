# Aitizaz.com

A simple static personal website.

## Local preview

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## GitHub Pages deployment

This repo includes a GitHub Actions workflow that deploys the site to GitHub
Pages on every push to `main`.

### Repo requirements

- The repository must be public for free GitHub Pages hosting.
- In GitHub, set **Settings → Pages → Source** to **GitHub Actions**.

### Custom domain

The `CNAME` file is already set to `aitizaz.com`.

Point your apex domain to GitHub Pages using these A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

If you want `www`, add a CNAME record pointing to `aitizazk.github.io`.
