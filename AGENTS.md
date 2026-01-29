I like to format my recipies in a simple markdown format.
- Each recipe should have its own folder.
- That folder should contain a README.md (all caps) with the recipe.
- The folder may additionally contain pictures of the dish, or other resources.
- The markdown recipe should start with the title (#), a line about the source of the recipe (if available), followed by the ingredients list (## Ingredients). Next should be the method (## Instructions) with subsections (e.g. ### Base and ### Topping) if needed.
- Recipies should be written in English by default, though translations can be provided e.g. as German.md files. The English versions should be the source of truth, and updated first in case of any changes.

## Detailed formatting

### Title
- Use `#` for the recipe name
- Include German name in parentheses if applicable: `# German Pancakes (Pfannkuchen)`
- Can add `[WIP]` tag for work-in-progress recipes

### Source attribution
- Place on the line immediately after the title, in italics
- For AI-generated recipes: `*Source: Recommended recipe from GPT 5.2 Thinking*`
- For adapted recipes: `*Adapted from [Name](URL) by ChatGPT.*`
- For recipes from people: `*Thanks to Sarah for finding & demonstrating the recipe! Original source: URL*`
- For web sources: `*Source: [Site Name, Author](URL)*`

### Brief description (optional)
- One line describing the dish, placed after the source
- Example: `Warm lemon-garlic chickpeas. Serves 2 as a side or 1 as a light main.`

### Ingredients
- Use `## Ingredients` or `## Ingredients (for X people)`
- Serving info can also go as a line below: `Makes ca. 16 big cookies.`
- Use `###` subsections for components (Dough, Topping, etc.)
- Format: `* 250g flour` - metric units, no space between number and unit
- Personal notes in parentheses: `* 50g sugar (ideally demerara, I used white)`
- Mark optional items: `* 1 green chilli, chopped (optional)`

### Instructions
- Use `## Instructions` or `## Instructions (ca. X min)` for time estimate
- Bullet points (`*`) for simple recipes, numbered lists for precise sequences (like baking)
- Use `###` subsections if needed (### Bottom, ### Topping, ### Finish)
- Written in imperative form, concise
- Personal notes and adjustments in parentheses: `Bake for 20-25 minutes at 155C fan (I used 175C I think)`
- Tips go inline or as a final `###` subsection (e.g. `### Advanced Version`), not a separate `## Tips` section

## Writing style
- Concise and practical, not formal
- Use abbreviations: tbsp, tsp, ca., min, pkg
- Metric units (g, ml, °C)
- Include helpful asides in parentheses
- OK to be slightly informal: "if you like", "mix everything together"
