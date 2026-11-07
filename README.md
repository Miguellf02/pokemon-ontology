# Pokémon Ontology

**Licensed to classify.**

An OWL ontology of the Pokémon world: creatures, types, base stats, moves, abilities, evolutions, generations and regions. Built at Universidad Politécnica de Madrid and published under a permanent identifier.

## Dossier

| | |
|---|---|
| **Identifier** | [`https://w3id.org/doisr/pokemon`](https://w3id.org/doisr/pokemon/) |
| **Prefix** | `pkmn:` |
| **Version** | 1.0.0 |
| **Inventory** | 11 classes · 19 object properties · 19 data properties |
| **Source intel** | [PokéAPI](https://pokeapi.co/) |
| **License** | CC BY 4.0 |

## Access

One identifier, every format. The IRI answers in whatever language you speak:

```bash
curl -L -H "Accept: text/html"           https://w3id.org/doisr/pokemon/   # documentation
curl -L -H "Accept: text/turtle"         https://w3id.org/doisr/pokemon/   # Turtle
curl -L -H "Accept: application/rdf+xml" https://w3id.org/doisr/pokemon/   # RDF/XML
```

Or read the [documentation](https://miguellf02.github.io/pokemon-ontology/release/1.0.0/index-en.html).

## Highlights

- `pkmn:LegendaryPokemon` is defined, not declared: a reasoner places legendaries automatically.
- Types and move categories are SKOS concepts, reusable outside the ontology.
- Provenance recorded with PROV-O.

## Cite

> López Ferreiro, M. (2026). *Pokémon Ontology*. https://w3id.org/doisr/pokemon

---
*Pokémon is a trademark of Nintendo, Creatures Inc. and GAME FREAK inc. This is an unofficial academic project.*
