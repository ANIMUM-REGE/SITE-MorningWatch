# Morning Watch — site

> Marketing, support, privacy, and terms pages for Morning Watch.

Static site for the app in [`APP-MorningWatch`](https://github.com/ANIMUM-REGE/APP-MorningWatch).
Part of the Perpetua app fleet (`VNTR-Perpetua`).

## Hosting

**No `CNAME` committed** — this site has no custom domain configured in the repo. If it is expected to be publicly reachable, verify how it is served before assuming it is.

## Pages

- `index.html`
- `privacy.html`
- `support.html`
- `terms.html`

## App status

Morning Watch is ✅ live on both the App Store and Google Play.

> Status drifts — **re-verify rather than trust this line.**
> `VNTR-Perpetua/company/state/app-fleet-status-2026-08-15.md` (as verified 2026-08-15)
> carries the fleet-wide picture and the method to re-derive it.

## Editing

Plain HTML, no build step — edit and commit. Keep privacy/support URLs stable: they
are referenced from live App Store and Play listings, and a broken support URL is a
review-rejection trigger.
