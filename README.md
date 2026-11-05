# Vera for Medic

Public entry point: https://irisyjchang.github.io/vera-for-medic/

This GitHub Pages entry forwards visitors to the existing AWS-backed combined Vera preview:
https://d3kk07plry56g2.cloudfront.net/vera-preview/

Combined application source:
https://github.com/NirmalKumarMari/medic-no-code-cht/tree/ui/vera-combined

GitHub Pages cannot run the Node API or AWS pipeline; the app and API stay together on their existing HTTPS origin. This repository does not redeploy or modify that AWS backend. The forwarding entry preserves query parameters and the existing QR-code URL.

The older static demo bundles and source.zip are retained as historical demo assets; they are not the current combined app. Their original source is main at f0a01aea9a2735793fcba587a6fe4ef7599df038. Original AGPL-3.0 license is preserved in LICENSE.
