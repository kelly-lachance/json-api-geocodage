# JSON, API et géocodage

Quête S09 — lecture de JSON imbriqué, interrogation d'API REST,
géocodage d'adresses et affichage sur une carte.

## Contenu

- `notebooks/quete_json_api.ipynb` : cours avec exemples guidés
- `challenge 1` : challenge 1 "Un JSON à deux étages" en autonomie pour assimilation du cours
- `challenge 2` : challenge 2 "Interroger une API en série" en autonomie pour assimilation du cours
- `challenge 3` : challenge 3 "Les restaurants de Catane, sur une carte" en autonomie pour assimilation du cours
- `data/` : les fichiers JSON de départ et le CSV géocodé produit

## Installation

python -m venv .venv
pip install -r requirements.txt

## Ce que fait le projet

Les trois challenges : aplatissement d'un JSON à deux niveaux,
géocodage d'une série d'adresses via l'API Adresse,
et cartographie de quatre restaurants de Catane via Nominatim.