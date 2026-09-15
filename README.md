# Ramen Misoya Spotlight — conversion prototype

Standalone bilingual redesign based on the existing Ramen Misoya Spotlight mockup.

The funnel is now Landing page → CTA → immediate secret reveal, with no form,
email, OTP or personal-data collection.

Events are pushed to `window.dataLayer`, mirrored in
`window.spotlightEvents` for QA, and sent through `gtag` when available.
UTM values are retained in `sessionStorage`.
Mockup pour le portrait de Derik
