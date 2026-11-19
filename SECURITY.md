# Security

Qvanta® builds quantum-safe security software. Treat this organization accordingly.

## Reporting a vulnerability

Do **not** open a public GitHub issue for security reports.

Use the contact flow on [qvanta.io](https://qvanta.io/Contact.dc.html) and mark the request as security-related, or email the address published on the company site contact page.

Please include:
- Affected product or repository (if known)
- Description and impact
- Steps to reproduce or a proof-of-concept (if safe to share)
- Your contact details for follow-up

We will acknowledge receipt and coordinate disclosure.

## Secrets and credentials

- Never commit API keys, tokens, private keys, `.env` files, or customer data.
- Prefer GitHub Actions secrets / org secrets for CI.
- Rotate any credential that may have been exposed.

## Supported surfaces

Security updates are delivered through Qvanta product channels and private repositories maintained by `@Qvanta-BigDx-Group/qvanta-team`.
