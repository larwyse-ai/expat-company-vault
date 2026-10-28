# Expat food costimator

Last reviewed: 2026-10-28 (historical starter summary, verify current version before any change)

## Scope
Food-only recipe and menu costing. Do not add beverage, coffee or sales-import features without an explicit requirement change.

## Historical baseline
- Tool: recipe and menu builder with sales pricing (v6 HTML build).
- Browser storage key `brewabar-recipe-system-v1` must be preserved, so existing data is not lost.

## Source of truth
- Recipes: the master recipe workbook for Expat Roasters food (2026 version).
- Branding and behaviour: historical handover package.

## Architecture
- Code hosted in the `expat-food-costimator` GitHub repository.
- A Supabase-backed foundation was planned and approved earlier. Confirm the live deployment and schema before making changes.

## Open items
- Confirm the latest production release.
- Confirm the monthly COGS upload workflow before updating this summary.

## Change log
- 2026-10-28: summary added to company vault (copied from personal vault starter, cleaned).
