# prodigi-tv

Encrypted internal dashboard for Prodigi.dev (office TV).

- `index.html`: the page design, encrypted with StatiCrypt (AES-256, client side). Readable only with the password.
- `data.enc.json`: the dashboard data, encrypted with AES-256-GCM (key derived from the same password with PBKDF2-SHA256).

No unencrypted data is stored in this repository.
