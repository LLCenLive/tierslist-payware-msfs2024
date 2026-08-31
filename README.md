# Tier List Airliners — MSFS 2024

Outil de tier list glisser-déposer pour classer les liners payware de MSFS 2024, aux couleurs LLCenLive (navy / glassmorphism / accent `#3b7fe8`).

C'est un **fichier unique** (`index.html`, HTML + CSS + JS intégrés) : aucune installation, aucun build. Tu peux l'ouvrir directement en double-cliquant dessus, ou l'héberger en ligne gratuitement en 2 minutes.

## Ajouter tes propres images

Le site cherche automatiquement une image par avion dans un dossier `images/` placé à côté d'`index.html`. Si le fichier existe, il s'affiche dans la carte. **S'il n'existe pas encore, la carte retombe automatiquement sur la silhouette vectorielle** — rien ne casse, tu peux illustrer au fur et à mesure.

### Règle de nommage

Le nom du fichier doit correspondre exactement à l'identifiant de l'avion (voir tableau ci-dessous), suivi de l'extension. Formats acceptés, testés dans cet ordre : **`.jpg` → `.jpeg` → `.png` → `.webp`**.

```
tierlist-msfs2024/
├── index.html
├── README.md
└── images/
    ├── fnx-a320.jpg
    ├── pmdg-777-300er.png
    ├── ini-a350-900.webp
    └── ...
```

Recommandations pour tes captures :
- Cadrage plutôt carré ou 4:3 (les vignettes sont recadrées en carré, `object-fit: cover`)
- 400×400 px minimum pour rester net sur les écrans HiDPI
- Le 3/4 avant de l'avion (vue extérieure) fonctionne mieux que le cockpit dans ce petit format

### Table de correspondance identifiant → avion

#### Fenix Simulations
| Fichier attendu | Avion |
|---|---|
| `images/fnx-a319.jpg` | A319 (CFM/IAE) |
| `images/fnx-a320.jpg` | A320 (CFM/IAE) |
| `images/fnx-a321.jpg` | A321 (CFM/IAE) |

#### Flight Sim Labs
| Fichier attendu | Avion |
|---|---|
| `images/fsl-a321ceo.jpg` | A321ceo |
| `images/fsl-a321neo.jpg` | A321neo (+ LR) |

#### PMDG
| Fichier attendu | Avion |
|---|---|
| `images/pmdg-737-600.jpg` | 737-600 (NG) |
| `images/pmdg-737-700.jpg` | 737-700 (NG) |
| `images/pmdg-737-800.jpg` | 737-800 (NG) |
| `images/pmdg-737-900.jpg` | 737-900 (NG) |
| `images/pmdg-777-200er.jpg` | 777-200ER |
| `images/pmdg-777-200lr.jpg` | 777-200LR |
| `images/pmdg-777-300er.jpg` | 777-300ER |
| `images/pmdg-777f.jpg` | 777F (Cargo) |
| `images/pmdg-dc6.jpg` | DC-6 (Classique) |

#### iniBuilds
| Fichier attendu | Avion |
|---|---|
| `images/ini-a300.jpg` | A300-600R |
| `images/ini-a310.jpg` | A310 |
| `images/ini-a320neo.jpg` | A320neo V2 |
| `images/ini-a321lr.jpg` | A321LR |
| `images/ini-a330-200.jpg` | A330-200 |
| `images/ini-a330-300.jpg` | A330-300 |
| `images/ini-a330-p2f.jpg` | A330-300 P2F (Cargo) |
| `images/ini-belugaxl.jpg` | Beluga XL (A330-743L) |
| `images/ini-a340.jpg` | A340 Airliner |
| `images/ini-a350-900.jpg` | A350-900 |
| `images/ini-a350-1000.jpg` | A350-1000 |
| `images/ini-l1011.jpg` | L-1011 TriStar (Classique) |
| `images/ini-707.jpg` | 707-320C (Famous Flyer) |
| `images/ini-skyvan.jpg` | SC.7 Skyvan (Local Legend) |
| `images/ini-ys11.jpg` | NAMC YS-11 (Local Legend) |

#### Aerosoft
| Fichier attendu | Avion |
|---|---|
| `images/as-crj550.jpg` | CRJ550 |
| `images/as-crj700.jpg` | CRJ700 |
| `images/as-crj900.jpg` | CRJ900 |
| `images/as-crj1000.jpg` | CRJ1000 |
| `images/as-twinotter.jpg` | Twin Otter (DHC-6) |
| `images/as-tl-a340600.jpg` | A340-600 Pro (Aerosoft × ToLiss) |

#### TFDi Design
| Fichier attendu | Avion |
|---|---|
| `images/tfdi-md11.jpg` | MD-11 (Tri-jet) |

#### Fokker
| Fichier attendu | Avion |
|---|---|
| `images/fok-f27.jpg` | F27 Friendship (iniBuilds/Microsoft) |
| `images/fok-f28.jpg` | F28 Professional (Just Flight) |
| `images/fok-f70.jpg` | F70 (Just Flight) |
| `images/fok-f100.jpg` | F100 (Just Flight) |

#### Flight Sim Studio
| Fichier attendu | Avion |
|---|---|
| `images/fss-727-100.jpg` | 727-100 (Tri-jet) |
| `images/fss-727-200.jpg` | 727-200 (Passagers) |
| `images/fss-727f.jpg` | 727 Freighter (Cargo) |
| `images/fss-e170.jpg` | E170 |
| `images/fss-e175.jpg` | E175 |
| `images/fss-e190.jpg` | E190 |
| `images/fss-e195.jpg` | E195 |

#### VirtualCol
| Fichier attendu | Avion |
|---|---|
| `images/vc-a220.jpg` | A220 |
| `images/vc-crj200.jpg` | CRJ-200 |
| `images/vc-dash8-100.jpg` | Dash 8-100 |
| `images/vc-dash8-200.jpg` | Dash 8 Q200 |
| `images/vc-dash8-300.jpg` | Dash 8 Q300 |
| `images/vc-e170175.jpg` | E170/175 |
| `images/vc-e190195.jpg` | E190/195 |

#### Latin VFR
| Fichier attendu | Avion |
|---|---|
| `images/lvfr-a318.jpg` | A318 |
| `images/lvfr-a319.jpg` | A319 |
| `images/lvfr-a320ceo.jpg` | A320ceo |
| `images/lvfr-a321ceo.jpg` | A321ceo |
| `images/lvfr-a321neo.jpg` | A321neo |
| `images/lvfr-a330-200.jpg` | A330-200 |
| `images/lvfr-a330-300.jpg` | A330-300 |
| `images/lvfr-a340-300.jpg` | A340-300 |
| `images/lvfr-a380.jpg` | A380 |

## Héberger gratuitement (3 options, 0€)

### Option 1 — Netlify Drop (le plus rapide)
1. Va sur https://app.netlify.com/drop
2. Glisse le **dossier complet** (`index.html` + `images/`) dans la zone de dépôt
3. Netlify te donne une URL en `.netlify.app` immédiatement, modifiable dans les réglages du site

### Option 2 — GitHub Pages (si tu veux un dépôt versionné)
1. Crée un repo GitHub (ex. `tierlist-msfs`)
2. Mets `index.html` et le dossier `images/` à la racine
3. Repo → **Settings → Pages → Deploy from branch → main / (root)**
4. Ton site est en ligne sur `https://<ton-pseudo>.github.io/tierlist-msfs/`

### Option 3 — Cloudflare Pages ou Vercel
Même principe : connecte le repo GitHub ou glisse le dossier, aucun réglage de build nécessaire (site statique).

## Personnaliser

- **Couleurs / accent** : tout est piloté par les variables CSS en haut du `<style>` (`--accent`, `--bg`, etc.)
- **Police Evogria** : le fichier utilise Rajdhani en fallback. Si tu as la licence de ta police Evogria, dépose le `.woff2` dans un dossier `/fonts`, puis décommente le bloc `@font-face` en haut du `<style>`.
- **Ajouter/retirer un avion** : tout est dans le tableau `AIRCRAFT` en JS (`id, nom, sous-titre, [studios], catégorie, silhouette`). Une ligne = une carte. L'`id` détermine aussi le nom de fichier image attendu.

## Fonctionnement

- Glisser-déposer tactile et souris (Pointer Events natifs, pas de librairie externe)
- Filtres par studio + recherche texte dans le hangar
- Export de la tier list en PNG (bouton "Exporter en image") pour la partager sur Twitch/Discord/X
- Aucune donnée envoyée nulle part : tout se passe dans le navigateur
