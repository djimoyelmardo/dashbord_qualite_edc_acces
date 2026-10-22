# Contrôle qualité des données d'accessibilité PMR d'Anglet

Tableaux de bord du contrôle qualité (ISO 19157) des données de cheminement piéton accessible d'Anglet (standard CNIG), de l'offre de transport (GTFS) et des sources associées. Projet EDC A3/A4.

**Site** : https://djimoyelmardo.github.io/dashbord_qualite_edc_acces/

| Page | Contenu |
|---|---|
| [`tableau_bord_qualite_v3.html`](tableau_bord_qualite_v3.html) | Base de travail du projet : recette de la livraison, base intégrée, offre GTFS, sources externes |
| [`tableau_bord_qualite_supabase.html`](tableau_bord_qualite_supabase.html) | Base partagée du groupe (Supabase « pmr_base ») : 93 contrôles alignés sur la base du projet (11/10/2026), cinq domaines |
| [`prototype/`](prototype/) | Prototype de l'application PMR (version publique, 22/10/2026) : réseau classé, itinéraire selon sept profils, cartes thématiques, mode présentation. Sans les secteurs prioritaires ni les travaux, réservés à un usage interne par la Ville ; police et bibliothèque cartographique servies avec la page (aucun service tiers). Produit par `outils/prototype_web.py` (variable `PROTO_PUBLIC`) |

Les pages sont autonomes (données intégrées, aucune connexion à une base) : les chiffres sont figés à la date de génération indiquée en tête de chaque page. Elles sont produites depuis le dépôt du projet par `outils/tableau_bord_qualite.py` et `outils/tableau_bord_qualite_supabase.py`, puis recopiées ici.

Prototype construit sur les données réelles d'Anglet (relevé CNIG publié par la Ville), pour démontrer une méthode de contrôle applicable au territoire de l'étude de cas (agglomération de Losse-en-Gelaisse, fictive).
