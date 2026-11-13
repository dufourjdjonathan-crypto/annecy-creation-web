# Annecy Création Web — guide du logo

## Le logo
- **Logo principal (piste B « Curseur ») :** un A en forme de montagne. Sa barre flotte, comme un curseur de texte qui clignote : Annecy et le code réunis.
- **Favicon / icône d'appli (piste C « Lignes de lac ») :** dans un carré arrondi, des sommets au-dessus d'un lac fait de lignes de code.

## Couleurs
| Nom | HEX | RGB | Usage |
|---|---|---|---|
| Bleu nuit | `#011F52` | 1, 31, 82 | Texte « Annecy », fonds sombres, fond de l'icône |
| Bleu profond | `#054B8D` | 5, 75, 141 | Le A du symbole |
| Bleu moyen | `#0E6DAA` | 14, 109, 170 | « CRÉATION WEB », montagnes de l'icône, boutons |
| Bleu ciel | `#3093C5` | 48, 147, 197 | Barre-curseur, lignes du lac |
| Cyan clair | `#6DC5E3` | 109, 197, 227 | Accents sur fond sombre |

Sur fond sombre, utilisez les versions `-sombre` / `-libre` (A blanc, curseur cyan). Le bleu profond se voit mal sur le bleu nuit.

## Versions (`svg/`, `png/`)
- `horizontal-*` : la version par défaut (en-tête de site, signature mail, devis).
- `empile-*` : pour les formats carrés ou étroits (réseaux sociaux, enseigne).
- `symbole-*` : le A seul, quand le nom est déjà écrit à côté.
- `icone-*` : l'icône carrée (piste C), pour l'appli et les réseaux sociaux.
- `favicon-petit-*` : un dessin simplifié pour les tailles de 48 px et moins.
- Déclinaisons : `couleur`, `sombre`/`libre` (fond sombre), `noir`, `blanc`, `mono` (bleu nuit seul).

## Règles
- **Zone de protection :** gardez autour du logo un espace vide au moins égal à la hauteur de la barre-curseur × 2.
- **Tailles minimales :** logo horizontal 120 px de large (30 mm en impression). Symbole 24 px. En dessous de 48 px, utilisez `favicon-petit`.
- **À ne pas faire :** déformer le logo, changer ses couleurs, ajouter des ombres ou des dégradés, réécrire le nom dans une autre police, poser la version couleur sur une photo chargée.

## Web (`web/`)
Copiez le contenu de `web/` à la racine du site, puis collez `head-snippet.html` dans le `<head>`.

## Typographie
Le nom est écrit en **Inter** (ExtraBold pour « Annecy », SemiBold espacé pour « CRÉATION WEB »). Inter est sous licence SIL OFL, l'usage dans un logo est permis. Dans les fichiers, le texte est déjà converti en tracés.

## À savoir
- Nous ne pouvons pas garantir que la marque est libre. Faites une recherche à l'INPI / l'EUIPO avant le dépôt.
- Pour l'impression, faites établir les équivalents CMJN / Pantone par votre imprimeur, sur épreuve.
