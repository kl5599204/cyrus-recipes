# Cyrus Recipes

A bilingual recipe library for Traditional Chinese and English, published with GitHub Pages.

## Features

- Search, cuisine and dish-type filters
- Serving adjustment starting at 3 portions
- Favourites saved in this browser
- Metric ingredient quantities
- Print-friendly recipe cards
- Bilingual kitchen tips and cooking notes
- Recipe updates only after the user confirms the finished recipe

## Recipe workflow

When a recipe is completed in a chat, present a clear **Add to website** or **Keep in chat** choice. Only add or update the matching recipe after the user chooses **Add to website**. Merge revisions into the existing best version instead of creating near-duplicates.

Recipe data belongs in `data/recipes.json`. Keep the English and Traditional Chinese title, ingredients, and steps together, and include cuisine, dish type, tags, base servings, timing, and source notes.

## GitHub Pages

The repository includes a GitHub Actions workflow that deploys the static site from the `main` branch. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source if Pages is not already enabled.

Food-safety references in the tips section link to the UK Food Standards Agency.
