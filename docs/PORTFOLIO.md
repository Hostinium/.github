# Hostinium Public Portfolio

This portfolio structure exists to present Hostinium products publicly without exposing internal implementation, customer-specific delivery details, or sensitive operating logic.

## Portfolio Model

Hostinium uses a two-layer public portfolio structure:

1. Organization-level positioning through the Hostinium GitHub profile.
2. Product-level public assets through showcase repositories or short public briefs.

## Current Public Assets

| Product | Public Presence Type | Public Path | Source Visibility |
| --- | --- | --- | --- |
| Benthium | Dedicated showcase repository | [Hostinium/Benthium-Showcase](https://github.com/Hostinium/Benthium-Showcase) | Private source |
| CaptureXPro | Portfolio brief | docs/products/CaptureXPro.md | Private source |
| qless | Portfolio brief | docs/products/qless.md | Private source |
| DrPure Platform | Portfolio brief | docs/products/DrPure-Platform.md | Private source |

## Public Boundary

Included publicly:

- business problem framing
- product category and use case
- high-level architecture direction
- delivery posture and platform qualities
- safe, short product summaries

Excluded publicly:

- internal source code
- environment configuration
- production data and customer workflows
- implementation details that materially reduce product defensibility
- delivery-specific documents, playbooks, and operating secrets

## Showcase Pattern

When a product needs stronger public presentation, use this order:

1. Public product summary on the Hostinium organization page.
2. Standalone public showcase repository if the product merits deeper presentation.
3. Links back to Hostinium as the company identity anchor.

## Positioning Rule

Every public asset should make three things clear:

- Hostinium is the company identity.
- The product solves a real operational problem.
- The public material is intentionally summary-level, not implementation-level.
