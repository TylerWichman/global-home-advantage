# Home Advantage Explorer

Parameter-driven Tableau dashboard analyzing 153K+ soccer matches across 27 countries (2000–2026), exploring how nation, travel distance, and elevation gap relate to home-field advantage.

🔗 [Live dashboard on Tableau Public](https://public.tableau.com/app/profile/tyler.wichman7836/viz/Home_Field_Advantage_Explorer/Dashboard1)

## Highlights
- Home advantage ranges from 0.51 (USA) to 0.17 (Japan) in average goal differential
- Effect strengthens with travel distance and elevation gap

## Stack
SQL (joins, CTEs, window functions) → Tableau (parameters, LOD expressions, dynamic titles)

## Files
- `/sql` — extraction and transformation queries
- `tableau_extract.csv` — final modeled dataset
- `home_advantage.twbx` — packaged Tableau workbook
