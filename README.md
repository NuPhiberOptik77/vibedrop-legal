# vibedrop-legal — redirect stubs only

The legal documents moved to [echodrop-legal](https://nuphiberoptik77.github.io/echodrop-legal/) when the repo was renamed
to drop the retired VibeDrop brand from the public URL.

GitHub does **not** reliably redirect a renamed repo's Pages path, and
`LEGAL_URLS` in the app is baked into shipped bundles — so any build that has
not taken the OTA still requests these old paths. Every file here is a redirect
stub to its counterpart in `echodrop-legal`. Do not add real content.

Retire this repo only once no build in the wild still points at these URLs.
