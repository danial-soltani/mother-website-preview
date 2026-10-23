# HOKARI — Early Public Launch (V9.0)
Prepared 2026-10-23 from the approved RP4 taxonomy and V8.9 readiness plan.

## Status
**CODE READY IN THIS BRANCH — NOT YET LIVE.** A Render static-site creation request was rejected with HTTP 402: the Render workspace requires payment information. Nothing has been deployed to Render.

## Publishing once billing/deployment is available
- Repo: danial-soltani/mother-website-preview
- Branch: launch/hokari-v9-early-20261023
- Build command: `echo static-site-ready`
- Publish directory: `site`
- Temporary address: static host default domain, not yet assigned.
- Connect the final brand domain only after name/domain ownership is confirmed.

## Release scope
Public English-first and Persian pages for home, COCO Studio hub, work, products, four industry solution categories, contact, and privacy.
COCO Studio is a separate app family; Pet Life, coaching and physical products are NOT members of COCO Studio.
No fake download links. No publicly exposed admin sandbox. No request submission until a protected backend is connected.
Brand name HOKARI remains provisional; only publish publicly when user approves the placeholder brand.
All pages currently have **noindex** and robots disallow crawling; this is intentional for the first private QA deployment. Before the public SEO launch, replace robots.txt, remove noindex, confirm canonical/hreflang on the *actual domain*, publish a sitemap, and validate EN/FA content.
Powered by HOKARI styling in `site/assets/powered-by-hokari.css`. Add a discreet backlink on *authorized* client projects only. Do not imply endorsement without client permission.

## Risk / release gates
1. DNS or host default URL tested, HTTPS verified.
2. EN/FA navigation, responsiveness and links tested on production.
3. Public contact path accurate (do not use fake forms).
4. Copyright/license and product publication approvals.
5. Performance test on mobile and static asset size.
6. Final Ready-phase subtle lighting adjustment as requested by owner.
7. Activate indexing only after approved site and domain are live.
