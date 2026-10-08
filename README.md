# at-automation-runtime

The hosted engine for [at-automation](https://github.com/chouglesaud/at-automation). `runtime.js` runs workflow JSON (router, condition, loop, find/create/update/upsert/delete, HTTP, chat, email, SMS, Claude, transform, wait) inside an Airtable "Run a script" action.

Generated scripts fetch this file from a CDN and verify its SHA-256 before running it:

```
https://cdn.jsdelivr.net/gh/chouglesaud/at-automation-runtime@main/runtime.js
```

Pin to a tag (`@v1`) for stable behaviour. **This file is generated** from `src/core/runtime.js` in the main repo (`npm run build:runtime`) — don't edit it here.
