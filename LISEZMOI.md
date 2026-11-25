# RDM Atelier

Calculs de résistance des matériaux (PWA) : traction, compression + flambement,
cisaillement, flexion (7 cas de poutre), torsion, force 3D sur bras encastré.

Mise en ligne : crée un dépôt (ex. `rdm-atelier`), envoie ces fichiers à la racine,
puis Settings → Pages → branche `main`, dossier `/ (root)`. Ensuite, sur le téléphone :
« Ajouter à l'écran d'accueil ». Fonctionne hors connexion.

Unités : longueurs en mm, contraintes en MPa (N/mm²), forces en N, daN ou kN (réglage en haut).
Les valeurs matière sont typiques : vérifie toujours la fiche de ta nuance.
Outil d'aide au pré-dimensionnement : il ne remplace pas une note de calcul validée
pour du levage ou de la sécurité des personnes.

## Onglet « Code de calcul » (CODAP ou autre)

L'appli ne contient aucune règle de code de construction. Pour activer l'onglet, glisse
dans l'appli (ou choisis avec le bouton) ton fichier référentiel `.json` et tes PDF.
Tout reste stocké sur l'appareil (IndexedDB), rien n'est envoyé.

**Ne mets jamais le référentiel ni les PDF dans le dépôt GitHub** : ils sont sous licence.
Garde-les sur ton téléphone / PC et glisse-les dans l'appli installée.

La liseuse PDF se télécharge (pdf.js) à la première ouverture d'un PDF, il faut donc
une connexion cette fois-là ; ensuite elle marche hors ligne.
