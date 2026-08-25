# Changelog

All notable changes to the **Apify for Grok Build** plugin are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed
- Apify MCP server URL now includes a `client=grok+build+plugin` query parameter (`https://mcp.apify.com/?client=grok+build+plugin`).

## [1.0.0] — Initial Grok Build release

### Added
- `apify` MCP server entry pointing to `https://mcp.apify.com/`.
- `.grok-plugin/plugin.json` manifest with plugin metadata.
- Apache-2.0 license.