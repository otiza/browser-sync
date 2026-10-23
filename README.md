# browser-sync

Self-hosted, client-side encrypted vault for Chromium browser identities (cookies + site storage). Push/pull named identities for the current site; optional auto-sync; multi-user.

## Status

Early setup. Product iterations live in GitHub milestones/issues once code starts. Local planning/progress notes are kept outside version control on the author machine.

## Stack (planned)

- Chromium extension (Manifest V3)
- Self-hosted multi-user API
- Client-side encryption (passphrase → KDF → AES-GCM); server stores ciphertext only

## License

TBD
