# SHADDOWWATCH public website

This repository contains the public SHADDOWWATCH website and navigable product-interface pages, deployed as static assets from `public/` on Render.

## Architecture and safety

- This is a public informational site with a production-oriented responsive design. It is **not** the authenticated product backend.
- Public user accounts, research/monitoring execution, and payment checkout are disabled because backend integration and merchant approval are pending.
- No secrets, internal provider credentials, or original app backend should be added to this public repository.
- Product paths are under `public/product/`. Historical dashboard URLs under `public/preview/` redirect to product pages.
- Static assets are in `public/assets/`; navigation is server-rendered in HTML and does not require JS.

## Next steps before commercial launch

1. Confirm legal merchant name and business address as per KYC and publish required information.
2. Approve final paid-service terms, refund timing, taxation, and entitlement rules.
3. Verify pricing, 2M/8M/20M planned monthly AI Token quotas, provider usage metering, and final product features.
4. Connect and test the private authenticated backend, if product access is to be offered.
5. Obtain payment-provider review approval before enabling live customer checkout.

## Deploy

This site serves the contents of `public/`. Render is configured for manual deployments; push changes then trigger deploy from Render.
