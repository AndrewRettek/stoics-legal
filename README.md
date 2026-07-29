# stoics-legal

Jekyll source for **stoics.chat** — the public support and legal site for the
Stoics iOS app.

| Page | URL |
|---|---|
| Support (home) | `https://stoics.chat/` |
| Support | `https://stoics.chat/support/` |
| Privacy Policy | `https://stoics.chat/privacy/` |
| Terms of Service | `https://stoics.chat/terms/` |

`https://stoics.chat/` is the **App Support** URL on the App Store listing, so
the home page must always lead with a contact method. `/support/` serves the
same content at the conventional path.

## Editing

Support copy lives once, in `_includes/support-body.md`, and is included by
both `index.md` and `support.md` so the two cannot drift.

`_config.yml` sets `header_pages` explicitly. Anything not listed there stays
out of the site navigation — add a page to that list deliberately, or it will
not appear.

## Before adding a page

Everything in this repo is public and reachable from the App Store listing.
Do not commit internal notes, review checklists, or anything not written for
users. A file here is a published page.
