# Ecosysteme MAIF

**Live:** https://shaynelarocque.github.io/EcosystemeMAIF/

An interactive knowledge graph visualizing the ecosystem of actors relevant to MAIF's response to climate-related emergencies — specifically heat waves and flooding — in France.

This was produced as part of a research project at [Strate École de Design](https://www.strate.design/) in Paris. Strate's interaction design team was tasked with generating design recommendations for [MAIF](https://www.maif.fr/), one of France's largest mutual insurance companies, on how they might better serve customers as climate events like extreme heat and flooding become more frequent.

## What this is

The visualization maps the relationships between the various actors in MAIF's ecosystem: government bodies at the federal and local levels, private companies, NGOs, activist movements, individuals, and key places. Each node type is color-coded, and edges represent the connections between them.

It was built with [Cosma](https://cosma.arthurperret.fr/about.html), an open-source tool for generating interactive network visualizations from structured data. The underlying data is managed in Google Sheets and rendered into a self-contained HTML file (`cosmoscope.html`) that can be opened directly in any browser.

## Viewing the visualization

Open `cosmoscope.html` in a browser. No server or build step required.

## Node types

| Type | Description |
|---|---|
| Gouvernement | National government |
| Gouvernement Fédérale | Federal government bodies |
| Gouvernement Locale | Local/municipal government |
| Organisation non gouvernementale | NGOs |
| Entreprises privées | Private sector companies |
| Individuels | Individual actors |
| Mouvement activiste | Activist movements |
| Lieux | Relevant places/locations |
| Connexion | Cross-cutting connections |

## Built with

- [Cosma v2.4.0](https://cosma.arthurperret.fr/about.html) — open-source knowledge graph visualization tool by Arthur Perret
- Google Sheets — for managing node and link data
- Custom CSS for interface styling

## Context

**Institution:** Strate École de Design, Paris
**Program:** Interaction Design
**Partner:** MAIF
**Research focus:** Design interventions for climate resilience — heat waves and flooding
**Data period:** March–April 2024
