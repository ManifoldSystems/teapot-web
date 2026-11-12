# Teapot Web

Static landing page for [Teapot](https://github.com/ManifoldSystems/teapot), a personal mesh for routing traffic through your own devices.

## Preview

Open `index.html` in a browser, or serve this directory locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`. No build step, dependencies, credentials, or control-plane access required.

## Links and scope

- [User guides](https://github.com/ManifoldSystems/teapot-docs) (docs site deployment pending)
- [Agent and CLI](https://github.com/ManifoldSystems/teapot)
- [Android exit node](https://github.com/ManifoldSystems/teapot-app)
- [Python client](https://github.com/ManifoldSystems/teapot-py)
- [Control plane](https://github.com/ManifoldSystems/teapot-control)

The marketing site is live at `https://teapot-iroh.vercel.app/`; it is not an authentication frontend. The agent, control plane, Android app, and Python client repositories are still private while being prepared for open source; those links currently require GitHub org access. The existing control dashboard lives at `https://teapot.example.com` and remains separate. Do not put admin tokens, device keys, or live node identifiers in this site.

Copy and commands should be checked against the [agent README](https://github.com/ManifoldSystems/teapot) before release. Do not advertise a package manager install or public download until one exists. No license has been chosen for this repository yet; public visibility does not grant reuse rights. See the [publication checklist](https://github.com/ManifoldSystems/teapot-docs/blob/master/PUBLICATION.md) for remaining OSS work.
