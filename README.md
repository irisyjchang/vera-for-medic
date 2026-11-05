# Vera for Medic

Public entry point: https://irisyjchang.github.io/vera-for-medic/

This GitHub Pages entry forwards visitors to a separate AWS-backed combined Vera demo:
https://d2wlzg1zcmviwl.cloudfront.net/vera-preview/

The demo runs in workshop account 851336929447, us-west-2, using Amazon Nova Lite through Bedrock. The app and Node API share the AWS HTTPS origin. GitHub Pages hosts the forwarding entry; its URL and existing QR code remain unchanged.

Combined application source:
https://github.com/NirmalKumarMari/medic-no-code-cht/tree/ui/vera-combined

Source commit: 2e99444dfbfb7a068c2b82ede12fe0b6156cddaf. The original repository is unchanged. The deployed worker adds binding of history warning IDs to the release approval gate, verified to reject missing acknowledgements.

The deployed demo passed a synthetic request, revision after content rejection, content approval, CHT compilation, two branch/golden-case tests, release approval, and downloadable artifact integrity checks. Demo personas are for synthetic/public data only. Releases download a CHT project; a hosted CHT server and live installation/phone synchronization are not included. Workshop resources remain subject to the workshop lifetime.

The older static demo bundles and source.zip are retained as historical demo assets; they are not the current combined app. Original AGPL-3.0 license is preserved in LICENSE.
