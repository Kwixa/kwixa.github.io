# kwixa.github.io

Redirect stubs only. Shipped app builds (HotShot: Fireball Pool, HotShot Darts 1.0) bake in
`https://kwixa.github.io/hotshot/...` privacy and support URLs from before the custom domain, and the source
repos are now private (GitHub Pages cannot serve a private repo on the free plan). This public repo keeps those
URLs alive: each known path is a meta-refresh stub to `https://hotshot.kwixa.co.uk/<same path>`, and `404.html`
forwards every other `/hotshot/*` path by script. Nothing else lives here. Retire it once no shipped build
carries a github.io URL.
