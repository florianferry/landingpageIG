# Contexte, landing page Instagram

Mémoire du projet, niveau léger. Le code arbitre : `index.html` et `confirmation-testeur.html`. Ce
fichier explique le pourquoi, jamais le quoi.

Plafond : 60 lignes, 5 décisions. Au-delà, promouvoir au niveau complet (`wiki-kit.py promote
insta`).

## État

- Amorcé le 2026-08-03.
- Murmur est sur Google Play (`fr.murmurapp.app`) ; l’app iPhone attend la validation d’Apple
  (2026-10). L’encart affiche l’App Store « bientôt » sur iPhone : à relier à la fiche dès sa sortie.
- Le 1901 Nancy est une location courte durée (réservation via Cocoonr) : la carte mène à la
  réservation.

## Décisions

Une ligne par décision : le choix, la raison, ce que ça interdit, la date.

- Mesure d’audience par GTM (`GTM-M27JZQJN`), pas Vercel Analytics : le site est servi par GitHub
  Pages (`CNAME`), un script Vercel n’y remonterait rien. 2026-10-28.
- Encart Photowall retiré : le code FLO15 n’est plus valable. Ne pas le remettre sans nouveau code.
  2026-10-28.
- Pas de newsletter : aucun e-mail n’est envoyé aux inscrits, le formulaire est retiré et le plan du
  rack se télécharge sans inscription. Ne pas remettre de capture d’e-mail sans envoi derrière.
  2026-10-28.
- Florian ne rénove pas qu’à Nancy : Nancy n’apparaît qu’avec Le 1901, son dernier chantier, pas
  dans l’en-tête ni le titre. 2026-10-28.

## Pièges

Ce qui a coûté du temps une fois et le recoûtera sans cette ligne.

- Nancy est la ville de l’Art nouveau, pas une « cité thermale » : la carte du 1901 l’avait écrit.
- Le CSV du catalogue sort d’un tableur avec des lignes vides en fin de fichier (`;;;;;;;;`). La
  page les filtre, mais elles faussent le décompte : nettoyer après chaque export.

## Questions ouvertes

Rien encore.
