# Plant Store Documentation

Welcome! This repository powers your Plant Store documentation site, built with [Fern](https://buildwithfern.com/). You're in the right place to understand how it works and make changes.

## What's in This Repo

- **Docs content** `fern/docs/` Your landing page, guides, and custom styling (fonts, CSS, logos)
- **API spec** `fern/openapi/api.yml` The OpenAPI definition that drives your API Reference
- **Configuration** `fern/docs.yml` (site title, layout, colors, navigation) and `fern/fern.config.json` (organization settings)

## Quick Start

1. **Install the Fern CLI**
   ```bash
   npm install -g fern-api
   ```

2. **Preview locally**
   ```bash
   fern docs dev
   ```
   Your docs will be available at `http://localhost:3000`.

3. **Publish changes**
   ```bash
   fern docs publish
   ```

## Making Changes

- **Edit content** Update pages in `fern/docs/pages/` (e.g. `landingpage.mdx`)
- **Update API reference** Edit `fern/openapi/api.yml` to add or change endpoints
- **Customize look and feel** Tweak `fern/docs.yml` for layout and colors, or `fern/docs/assets/main.css` for styling

## Learn More

For deeper guidance on Fern Docs, check out the [Fern Docs overview](https://buildwithfern.com/learn/docs/getting-started/overview).
