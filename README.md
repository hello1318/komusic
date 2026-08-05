# komusic

## Résumé du fichier text.html

Le fichier `text.html` est une page HTML très simple qui présente le projet KoMusic et une petite tracklist. Voici ce qu'il fait :

- Affiche un titre et un sous-titre présentant KoMusic.
- Liste deux morceaux, chacun avec :
  - un titre (balise `<h4>`),
  - un court crédit (<small>) demandant d'attribuer la musique à `@koacdpƙ`,
  - un bouton qui ouvre le fichier audio associé sur Google Drive (`target="_blank"`) pour écouter ou télécharger.
- Propose un lien/bouton vers un Google Form pour permettre aux visiteurs d'envoyer leur propre musique.
- Utilise une structure HTML minimale (doctype, head avec charset et title, body avec headings, paragraphes, liens et boutons).

Remarque : le fichier `text.html` contient à la fin un fragment dupliqué/malveillant (des lignes répétées/finales mal placées) ; il serait conseillé de nettoyer ce doublon pour garantir un HTML valide.

---

Usage rapide

- Pour écouter un morceau : cliquer sur le bouton "Écouter / Télécharger sur Google Drive" correspondant.
- Pour proposer une musique : cliquer sur "Envoyer une musique" (le formulaire s'ouvre dans un nouvel onglet).
