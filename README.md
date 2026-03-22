# README

## Quick Start
To get started with your Shopify theme, follow these instructions to set up your environment and customize your store.

## Prerequisites
- A Shopify store.
- [Shopify CLI](https://shopify.dev/tools/cli) installed (if using this installation method).
- Basic understanding of HTML, CSS, and Liquid.

## Installation Methods

### 1. Shopify CLI
1. Install the Shopify CLI if you haven't already.
2. Run `shopify theme init <theme-name>` to create a new theme.
3. Navigate into your theme directory with `cd <theme-name>` and run `shopify theme serve` to start a local development server.

### 2. Direct Upload
1. Download your theme as a ZIP file from your local machine.
2. Log in to your Shopify admin.
3. Go to **Online Store > Themes**.
4. Click on **Upload theme** and select your ZIP file.

### 3. Git Sync
1. Clone your theme repository using `git clone <repository-url>`.
2. Make changes locally and push them back to the repository.
3. Use the Shopify CLI to sync changes or set up a deployment pipeline.

## Development Setup
- Use [Shopify Theme Kit](https://shopify.dev/tools/theme-kit) for efficient development.
- Set your local environment to use the provided `.env` files to keep sensitive information secure.

## Theme Structure
- **config/** - Contains configuration files.
- **layout/** - Layout templates.
- **templates/** - Page templates.
- **sections/** - Dynamic sections.
- **snippets/** - Reusable components.
- **assets/** - Theme assets (images, styles, scripts).

## Customization Guide
1. Access the **Theme Editor** from your Shopify admin to customize your theme's appearance.
2. Modify settings in the `config/settings_data.json` file for more advanced settings.

## Common Tasks
- Add a new section: Create a `.liquid` file in the `sections/` directory.
- Modify styles: Edit CSS files located in the `assets/` directory.

## Troubleshooting
- If your theme doesn't appear, ensure it's published and that you're viewing the correct store.
- For issues with Shopify CLI, refer to the CLI logs for error messages.

## Resources
- [Shopify Theme Development](https://shopify.dev/themes)
- [Shopify Liquid Documentation](https://shopify.dev/api/liquid)
- [Shopify CLI Documentation](https://shopify.dev/tools/cli)