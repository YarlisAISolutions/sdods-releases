# SDODS releases

Installers for the [SDODS](https://sdods.com) desktop app. **This repository holds no source** —
only published release artifacts, and the apt repository served from its `gh-pages` branch.

It exists separately because release assets on a private repository are private too, so a download
link from sdods.com would 404 for every visitor.

## Downloads

<https://sdods.com/download> picks the right file for your platform. Every release also carries
`SHA256SUMS.txt`:

```bash
sha256sum -c SHA256SUMS.txt --ignore-missing
```

## apt

Debian and Ubuntu users can install the desktop app from the signed repository on `gh-pages`. The
two setup lines are in [the installation guide](https://docs.sdods.com/docs/getting-started/installation/).
