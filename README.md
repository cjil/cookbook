 # Cookbook

This repository is a personal cookbook: a collection of recipes you have found or created, stored as Git-friendly Markdown so they are easy to search, edit, and share.

## Purpose
- Keep a single source of truth for your recipes.
- Maintain consistent formatting so recipes are easy to read and publish (e.g., GitHub Pages).
- Preserve attribution and notes alongside each recipe.

## Repository structure (overview)
- `Template.md` — the recipe template to follow when adding new recipes.
- `BBQ/` — BBQ recipes and subfolders (e.g., `Rubs/`).
- `LICENSE` — repository license.

## How to add a recipe
1. Copy `Template.md` into the appropriate folder and rename it to a descriptive filename (e.g., `My-Pancake.md`).
2. Fill in the sections: Recipe Details (Servings, Difficulty, Prep time, Cook time, Tags, Categories), Preamble, Ingredients, Instructions, and Attribution.
3. Commit and push your changes.

## Template fields
- Recipe Details: include `Servings`, `Difficulty`, `Prep time`, `Cook time`, `Tags`, and `Categories` for consistency and searching.
- Preamble: short note about origin or inspiration.
- Ingredients: list with measurements (note which quantity the recipe is scaled to).
- Instructions: numbered steps for preparation and cooking.
- Attribution: source and notes.

## Tags and searching
- Markdown files do not have built-in per-file tags on GitHub. Keep `Tags:` and `Categories:` in the recipe body for human-readable metadata and repository-wide text search.
- For richer per-file metadata (used by static site generators), consider switching to YAML frontmatter at the top of each recipe with `tags:` and `categories:` keys.

## Automation and authoring help
This repo includes a custom agent for authoring and standardizing recipes: `.github/agents/cookbook.agent.md`. Use it to create or revise recipes that conform to the template.

## Publishing
If you want to publish this cookbook as a website, use a static site generator (Jekyll, Hugo) and convert `Tags`/`Categories` to YAML frontmatter so they can power indexes and collections.

## License
See `LICENSE` for licensing details.

Enjoy cooking — and feel free to open issues or pull requests when you improve recipes or the template.

