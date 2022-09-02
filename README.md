# signadot-sandbox-apply-action

Applies a sandbox template to your [Signadot sandbox environment](https://docs.signadot.com/docs/overview/).

Based on https://docs.signadot.com/docs/github-ci-integration.

## Usage

Requires `secret.SIGNADOT_API_KEY`.

```
uses: beejiujitsu/signadot-sandbox-apply-action@v1
with:
    image: image/name:tag
    signadot_org: some_org # from https://app.signadot.com/settings/global
```