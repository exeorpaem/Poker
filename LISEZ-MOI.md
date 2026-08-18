# Entraîneur Poker — dossier prêt à héberger

Ces 5 fichiers suffisent. Une fois en ligne, l'app s'installe sur le téléphone
(« Ajouter à l'écran d'accueil ») et fonctionne ensuite hors ligne.

## Option A — GitHub Pages (gratuit, 5 minutes)

1. Crée un compte sur github.com, puis un dépôt public (bouton « New »), par exemple `poker`.
2. Sur la page du dépôt : « Add file » → « Upload files » → dépose les 5 fichiers de ce dossier
   (index.html, manifest.json, sw.js, icon-192.png, icon-512.png) → « Commit changes ».
3. Onglet « Settings » → « Pages » → Source : « Deploy from a branch », branche `main`, dossier
   `/ (root)` → « Save ».
4. Attends 1 à 2 minutes : l'adresse s'affiche, du type
   `https://TON-PSEUDO.github.io/poker/`. Ouvre-la sur ton téléphone.
5. Menu du navigateur → « Ajouter à l'écran d'accueil ». L'icône apparaît comme une vraie app.

## Option B — Netlify Drop (encore plus rapide)

Va sur app.netlify.com/drop et glisse le DOSSIER entier. Une adresse est générée aussitôt.
(Compte gratuit demandé pour conserver le site au-delà de quelques heures.)

## Mettre à jour plus tard

Remplace `index.html` par la nouvelle version (même nom), et incrémente `poker-v2` en `poker-v3`
dans `sw.js` pour forcer le rafraîchissement du cache hors ligne.

## Ta progression

Elle est stockée par le navigateur, liée à l'adresse du site : garde la même adresse et tout
reste en place. Pense à exporter ta sauvegarde de temps en temps (Réglages → Exporter).
