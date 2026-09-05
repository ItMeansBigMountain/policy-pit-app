# Policy Pit

An explicitly labeled development preview of a swipeable, opposing-policy comparison flow. This scaffold uses fictional candidates and illustrative local data. It is not a finished product, a source of political facts, a crowd survey, or production software.

Public development preview: https://policy-pit-app.vercel.app

## Run locally

```sh
npm ci
npm run check
npm run dev
```

No environment variables or external services are required for this slice. Local configuration belongs in `.env`; never commit real secrets.

## What works

- Review three sample policy comparisons.
- Choose Blue, Red, or neutral/skip with keyboard, touch, or pointer controls.
- See an on-device session summary and restart the flow.

Selections exist only in page memory and disappear on refresh. There are no accounts, analytics, network submissions, or persistent crowd results.

## Remaining product decisions

- Which real politicians and jurisdictions are in scope.
- Source standards, citation display, freshness, and corrections.
- Whether candidate labels remain visible before a preference is recorded.
- Demographic collection, minimum cohort sizes, privacy, and moderation.
- Authentication, abuse controls, accessibility research, and legal review.

Deployment is development-only through `.github/workflows/preview.yml`. Preserve the existing Vercel project, canonical alias, and history. See `ROLLBACK.md`.
