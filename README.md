# Cockpit Achat — Groupe CAREXO

Outil d'aide à la décision d'achat véhicules. Fichier unique `index.html`, aucune installation.

Accès protégé par mot de passe. Les données restent dans ton navigateur ; branchement possible sur Google Sheets (ventes, stock concurrent, stock actuel VN/VO).

## Mettre en ligne sur GitHub Pages (≈ 3 min)

1. Va sur **github.com** → connecte-toi → bouton **New** (nouveau dépôt).
2. Nom du dépôt : par ex. `cockpit-achat`. Coche **Private** si tu veux (Pages fonctionne aussi en privé sur un compte Pro ; sinon laisse Public — tes données ne sont pas dans le fichier).
3. Crée le dépôt, puis **Add file → Upload files**.
4. Glisse **`index.html`** (et ce `README.md`) dans la zone d'upload → **Commit changes**.
5. Onglet **Settings → Pages**.
6. Section **Build and deployment** → Source : **Deploy from a branch** → Branch : **main** / dossier **/(root)** → **Save**.
7. Patiente 1–2 min. Ton URL s'affiche en haut de la page Pages :
   `https://TON-PSEUDO.github.io/cockpit-achat/`
8. Ouvre l'URL → écran de verrouillage → mot de passe → c'est en ligne.

Astuce : ajoute l'URL à l'écran d'accueil de ton téléphone pour un accès type application.

## Mettre à jour l'outil plus tard

Reviens dans le dépôt → **`index.html`** → icône crayon (ou réupload) → colle la nouvelle version → **Commit**. Pages se met à jour tout seul en 1–2 min.

## Brancher les Google Sheets

Dans l'outil, onglet **Sources** : colle l'URL CSV publiée de chaque feuille (Fichier → Partager → Publier sur le web → onglet + format CSV), puis **Charger**. Pour tes stocks VN/VO, publie de préférence un onglet « Vue Cockpit » sans les prix d'achat, ou alimente via n8n.
