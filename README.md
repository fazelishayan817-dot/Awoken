# Awoken

Monorepo regroupant quatre projets de décompilation/désassemblage de pret :

| Dossier | Jeu | Plateforme | Source | Commit |
|---|---|---|---|---|
| `pokered/` | Pokémon Rouge / Bleu | Game Boy | https://github.com/pret/pokered | `ba9c0568f64ae602fadda577a08c66639f93082a` |
| `pokecrystal/` | Pokémon Cristal | Game Boy Color | https://github.com/pret/pokecrystal | `9ce4c4e5068ffdf56e23ca3d8dc9178b2465d482` |
| `pokeemerald/` | Pokémon Émeraude | Game Boy Advance | https://github.com/pret/pokeemerald | `9103e529c2fbdd7add4a1ff3350c6c1f92112c42` |
| `pokeplatinum/` | Pokémon Platine | Nintendo DS | https://github.com/pret/pokeplatinum | `62bdaacdca6c56a6a396f3e9911e2f922b79bba8` |

Chaque dossier est une copie intacte du projet d'origine (sans son historique git).
Chaque projet se compile indépendamment : voir le `INSTALL.md` de chaque dossier.
Aucune ROM n'est incluse ; les ROMs de base doivent être fournies par l'utilisateur quand le projet en a besoin.
