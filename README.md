# safeterminal-config

Public fallback host for the SafeTerminal desktop client's runtime config:
prefer domains and DoH endpoints. Primary source is R2
(`https://storage.safeterminal.cloud/config/prefer-config.json`); this repo is
the fallback when the Cloudflare path is hijacked or blocked.

Edit the copy in `safeterminal-client-release/config/prefer-config.json` first,
then mirror it here. Content is intentionally public — it ships inside every
client binary.
