# Macaron 101 LLM Wiki — Schema & Operating Rules

## 1. Goal & Target Audience
- **Topic:** Baking Macaron 101: How Different Meringue Methods and Folding Techniques (*Macaronage*) Affect the Final Result.
- **Readers:** Complete beginners who have never made macarons or struggled with failed batches.
- **Strict Grounding Rule:** Every fact, ratio, temperature, and troubleshooting tip must come strictly from the 5 ingested sources in `raw_sources/`. Do not invent temperatures or ratios.

## 2. Wiki Architecture
- `wiki/index.md`: Master table of contents and 2-sentence summary of every concept page.
- `wiki/log.md`: Chronological record of every source ingested, conflicts caught, and verification checks performed.
- `wiki/concepts/01-meringue-methods.md`: Comparison of French, Swiss, and Italian meringue (process, stability, temperature, difficulty).
- `wiki/concepts/02-macaronage-folding.md`: Mechanics of folding dry ingredients into meringue, ready visual ("lava" / "figure-8"), and effects of under- vs. over-mixing.
- `wiki/concepts/03-prep-resting-baking.md`: Ingredient prep, skin formation (resting), oven temperature, and how "feet" form.
- `wiki/concepts/04-troubleshooting.md`: Diagnostic guide mapping shell failures (hollow, cracked, no feet, lopsided) back to meringue or folding errors.

## 3. Formatting & Verification Rules
1. **Citations Required:** Tag every claim with `[Source X]` (e.g., `[Source 1: CookbookManager]`).
2. **Cross-Linking:** Use `[[filename]]` links between related concept pages.
3. **Conflict Detection:** If two sources give different temperatures, resting times, or advice, explicitly document both in a `## Conflicts & Notes` section rather than silently picking one.
