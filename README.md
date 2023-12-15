# mre-outlook-auth

This repo is meant to reproduce an error during authentication that happens in New Outlook Desktop.

- Problem was reproduced using Outlook version 1.2023.1207.400 (Production) and client version 20231201002.07
- Problem is not reproducible with Outlook Online or the old desktop version

## Setup

```bash
npm run certificates
npm start
```

Provided for convenience, a way to check the validity of the manifest:

```bash
npm run validate
```
