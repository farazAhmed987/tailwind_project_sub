# Tailwind Project Sub

This repository is a small Tailwind CSS practice project for learning how to set up a basic styling workflow, build utility-based layouts, and generate compiled CSS from a source stylesheet.

## Purpose

The goal of the project is to practice Tailwind CSS fundamentals in a simple, local setup. It is useful for experimenting with utilities, testing layouts, and learning how Tailwind is configured and built.

## How It Works

The project uses a source CSS file in `Tailwind_projects/src/input.css` with the standard Tailwind directives:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Tailwind is configured in `Tailwind_projects/tailwind.config.js` to scan the generated HTML files in `Tailwind_projects/dist/`. When you build the project, Tailwind processes the source CSS and outputs the final styles into the compiled stylesheet.

## Project Structure

- `Tailwind_projects/src/` - source CSS input
- `Tailwind_projects/dist/` - compiled HTML/output files
- `Tailwind_projects/dst/` - additional output or style assets
- `Tailwind_projects/resources/` - supporting project resources

## Usage

1. Edit `Tailwind_projects/src/input.css`.
2. Update the HTML files inside `Tailwind_projects/dist/`.
3. Rebuild Tailwind CSS to generate the final styles.

## Notes

- This repository is intended for Tailwind CSS practice and experimentation.
- The config currently targets `./dist/*.html` files for content scanning.
