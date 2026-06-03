# ped_simulator_data

PUBLIC data mirror for the **Pediatric Case Author** (offline authoring Workbench).
Holds only the NON-sensitive files the artifact pulls:

- `taxonomy/archetypes.json` — archetype labels (id + EN/HU/DE + sub-specialty)
- `archetypes/<id>.json` — shared rubric definitions (skeleton + diagnosis pool + weights)
- `guides/` — guideline texts the Workbench can load (`_index.json` + `.md` files)

The application code and the actual cases (with diagnoses) live in the PRIVATE
`ped_simulator` repo. Keep these three folders in sync with that repo on release.
