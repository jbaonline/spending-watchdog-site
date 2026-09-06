# spending-watchdog-site

**Retired.** Valsiva's public site is now https://valsiva.com - repository
`jbaonline/valsiva-site`, deployed as a Cloudflare Worker.

This repository exists only to keep its old URLs resolving. They were
published to Plaid as supporting documents for the production application, and
a URL in someone else's records outlives the record; it has to keep working
whether or not the dashboard entry is ever updated.

Every page here is a redirect stub - canonical, `noindex, follow`, meta
refresh, `location.replace`, and a visible link, so it survives a browser with
no JavaScript and a reader with neither:

| Old URL | Now serves |
|---|---|
| `/` | https://valsiva.com/ |
| `/privacy/` | https://valsiva.com/privacy/ |
| `/policies/data-retention-and-deletion.html` | https://valsiva.com/policies/data-retention-and-deletion.html |

`policies/Infraxeon-Data-Retention-and-Deletion-Policy.pdf` is **not** a stub
and must not become one. It is the signed artefact of v1.0, and a document
someone downloaded from this path should still be that document. The copy on
valsiva.com is byte-identical.

Do not add pages here. Content belongs in `valsiva-site`.

Served via GitHub Pages from the `master` branch root.
