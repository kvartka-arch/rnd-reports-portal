# countries/

Each country that has at least one published report gets its own subfolder here.

Structure per country:
- `countries/<country-slug>/index.html` — country page listing all reports, grouped by analysis date.
- `countries/<country-slug>/<date>-<type>.html` — individual report pages.

Report types:
- `initial` — Initial Market Analysis (first deep research of a market).
- `update` — Periodic Market Update (monthly, quarterly, or ad-hoc).

Do not create a country folder until at least one report exists for that country.
