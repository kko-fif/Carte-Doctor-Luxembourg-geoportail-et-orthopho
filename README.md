# Carte médicale Luxembourg — correctif du 23 septembre 2026

Copier `index.html`, `assets/` et `data/` à la racine du dépôt GitHub Pages. Le tableau `controle_adresses.csv` peut rester hors du site public.

- Population RNPP officielle du 01/07/2026 intégrée localement pour les **100 communes** (693 913 habitants). Densité = médecins physiques uniques identifiés dans la commune ÷ population communale × 10 000 ; un médecin multisite compte une fois dans chaque commune où il exerce.
- **269/362 établissements** avec coordonnées Geoportail ACT conservées seulement si le numéro, la rue et le code postal concordent. Ces adresses représentent des implantations affichées sur la carte. **93 établissements** ont des adresses multiples, tronquées, ambiguës ou une réponse non concordante ; ils restent dans le tableau sans point inventé.
- `controle_adresses.csv` précise les 362 cas, les écarts de formulation entre fiches médecin et établissement, les adresses ACT acceptées et les éléments à vérifier.
- Les catégories de couleur suivent l'indicateur sélectionné. La spécialité et l'option hôpitaux modifient le calcul.

Doctena est une collecte partielle et non un registre officiel exhaustif. Une faible densité signifie une faible présence dans cette collecte, sans prouver un manque réel de médecins. Les positions validées automatiquement gagneraient à être vérifiées visuellement avant toute utilisation opérationnelle.
