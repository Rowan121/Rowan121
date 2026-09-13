## Hi there 👋. My name is Rowan, a student in the Informatics program at the University of Washington.

👉 **[Click here for my project!](https://github.com/Rowan121/they-say)**

## Featured projects

### [They Say — Ground Truthing](https://github.com/Rowan121/they-say)

<a href="https://rowan121.github.io/they-say/">
  <img src="https://raw.githubusercontent.com/Rowan121/they-say/main/docs/screenshot.png" alt="They Say citation-mutation graph visualization" />
</a>

An interactive knowledge graph that traces how a single mis-read paper fans out into "common knowledge." The case study is the hummingbird **1 : 4 sugar rule** (~20% sugar water) — advice that became gospel across blogs, guides, and retailers even though the papers it's attributed to never prescribed it, while an overlooked study found birds actually prefer a much higher (~50%) concentration.

- Ingested source PDFs into a **Neo4j** knowledge graph via GraphRAG document intelligence, extracting **840 claims** (with numeric findings) across 80 documents.
- Visualizes citation chains where edge **thickness** = citation strength and **color** = confidence the citation is faithful (mutated → red, faithful → green).
- Isolates the overlooked counter-truth so the "gospel" claim and the real evidence stand apart at a glance.

**Stack:** `Neo4j` `GraphRAG` `Cypher` `D3.js` `Python` `GitHub Pages`

[Live demo](https://rowan121.github.io/they-say/) · [Repo](https://github.com/Rowan121/they-say)

### [Hawaiʻi Wildfire Evacuation Explorer](https://github.com/Rowan121/hawaii-wildfire-evacuation-explorer)

<a href="https://rowancooper.me/hwmo-ai-roads/">
  <img src="https://raw.githubusercontent.com/Rowan121/hawaii-wildfire-evacuation-explorer/main/docs/assets/property-screening-tool.png" alt="Hawaiʻi Wildfire Evacuation Explorer property screening interface" />
</a>

A statewide GIS research prototype that explains property-level evacuation constraints and directional wildfire exposure using road networks, island-specific building sources, terrain, fuels, weather, and reported fire evidence.

- Expanded **581 hand-reviewed Kauaʻi access zones** into a statewide property-screening workflow.
- Evaluated a building detector across **8 islands and 196 source-agreement tiles**, with AI retained as a human-review queue rather than authoritative map truth.
- Built address and location search, explainable road routing, evidence overlays, a guided tutorial, and downloadable property reports.

**Stack:** `Python` `GeoPandas` `Shapely` `PyTorch` `Leaflet` `ArcGIS REST` `OpenStreetMap` `DigitalOcean`

[Live case study](https://rowancooper.me/hwmo-ai-roads/) · [Try the tool](https://rowancooper.me/hwmo-ai-roads/hawaii_fire_address_demo.html?tutorial=1) · [Behind the scenes](https://github.com/Rowan121/hawaii-wildfire-evacuation-explorer)
