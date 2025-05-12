# ChessOpenings — Base de données Excel des ouvertures d'échecs ♟️

Ce projet est une **base de données complète des ouvertures d’échecs** classées selon les codes ECO (Encyclopaedia of Chess Openings), conçue sous Microsoft Excel avec macros VBA.

Il inclut également un **lecteur de fichiers PGN** interactif, permettant de visualiser des parties annotées directement dans Excel, avec gestion des commentaires.

---

## 📌 Contenu du fichier `ChessOpenings.xlsm`

| Colonne | Description |
|---------|-------------|
| A       | Code ECO (ex : B01, C65...) |
| B       | Nom de l’ouverture |
| C       | Suite typique de coups |
| D       | Lien Wikipedia vers l’article de l’ouverture (en français) |
| E       | Titre généré avec noms, date, code ECO, et lien vers Wikipedia si disponible |
| F       | Contenu complet du fichier PGN |
| G       | Surnom de la partie (ex : "L’Immortelle", "La perle de Zukertort", etc.)

---

## 🧠 Fonctionnalités VBA

- 📂 Lecture du fichier PGN contenu dans la colonne F
- 🗂️ Affichage structuré dans une interface utilisateur (UserForm) avec :
  - N° de coup
  - Coup des Blancs / Noirs
  - Commentaires intégrés
- 🔎 Affichage des variantes possibles (optionnel ou supprimé)
- 📤 Export du fichier PGN temporaire vers Lucas Chess (si installé)

---

## 🚀 Utilisation

1. Activez les macros à l'ouverture du fichier Excel.
2. Cliquez sur une ligne contenant une partie PGN (colonne F).
3. La partie s'affiche dans une fenêtre avec commentaires.
4. Possibilité d'ouvrir automatiquement la partie dans Lucas Chess.

---

## 📢 Remarques

- Le fichier contient actuellement **plus de 2300 ouvertures**, mais seulement **quelques dizaines de parties illustratives** (en cours d’enrichissement).
- L’utilisateur peut ajouter lui-même ses fichiers PGN pour compléter sa base.
- Aucune mise à jour régulière n’est garantie — ce projet est fourni "tel quel", librement réutilisable.

---

## 📄 Licence

Ce projet est publié sous licence **MIT**. Vous pouvez l’utiliser, le modifier, et le partager librement.

---

## 📬 Contact / retour

Suggestions bienvenues ! Vous pouvez créer une "issue" sur GitHub ou me contacter directement.

---

## 🌍 English Summary (brief)

**ChessOpenings.xlsm** is a French-language Excel database of 2300+ chess openings, with an integrated PGN viewer (in VBA) and optional links to Wikipedia. Users can add their own PGN files. Free and open-source (MIT).
