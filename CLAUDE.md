# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Terra Relics™ is a satirical product concept website. The project consists of static files with no build system or dependencies.

## Files

- `index.html` - Single-page landing site with embedded CSS (no external stylesheets or JavaScript)
- `financials_pitch.md` - Investor pitch deck in markdown format

## Development

Open `index.html` directly in a browser to view. No build step or server required.

## Design Notes

The site uses CSS custom properties defined in `:root` for theming:
- `--ink`, `--muted` - Text colors
- `--soil`, `--leaf`, `--accent` - Brand colors
- `--bone` - Background color

Responsive breakpoint at 900px switches grid layouts to single column.
