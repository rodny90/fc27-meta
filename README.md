# fc27-meta

Gameplay-meta weights for the FC27 Toolkit's "Best XI for the meta" (EA SPORTS FC 27 Web App extension).

`meta.json` is data only: a JSON payload (the weights, a version and a serial) with an ECDSA P-256 signature.
The extension verifies the signature and every value before using it, and falls back to its built-in weights.
Published with `npm run meta:publish -- --push` from the extension project. Not affiliated with EA.
