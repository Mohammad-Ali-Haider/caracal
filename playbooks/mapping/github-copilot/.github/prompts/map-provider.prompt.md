---
description: "Map a provider dashboard form to visible Caracal Console provider fields."
argument-hint: "Provider name, provider type, dashboard labels, helper text, placeholders"
tools: [read, search, web]
---
# Map Provider

Map the provider dashboard fields to Caracal Console provider fields.

Steps:

1. Read `.github/console-fields.ground-truth.json`.
2. Ask for missing provider type, labels, helper text, placeholders, section headings, and setup steps.
3. Ask whether the provider is creating a client, application, API key, token, secret, or connector.
4. Validate with Caracal docs and official provider docs.
5. Ask for more evidence when labels or docs are incomplete instead of guessing.
6. Return the standard field mapping format.

Never repeat raw secrets.
Do not generate mock provider configs unless the user explicitly asks for examples.
