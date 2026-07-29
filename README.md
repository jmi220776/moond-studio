# MOOND STUDIO · site

Site statique. Aucune installation, aucun build. Les polices viennent de Google Fonts.

## Contenu

- `index.html` — accueil MOOND STUDIO
- `forum.html` — Une Famille Modèle
- `rms.html` — RATÉ MAIS STYLÉ (avec vraies images et affiche SANS PARLER)
- `vercel.json` — active les URLs sans extension
- `images/` — les huit visuels, déjà nommés et compressés

## Mettre en ligne (nouveau repo, PAS forum-laquatre)

1. Sur github.com : New repository, nom `moond-studio`, Create.
2. « uploading an existing file », glisser TOUT le contenu de ce dossier
   (les fichiers ET le dossier images), puis Commit changes.
3. Sur vercel.com : Add New → Project → importer `moond-studio`.
4. Framework Preset : **Other**. Ne rien changer d'autre. Deploy.
5. Vercel donne une adresse en .vercel.app. Le site est en ligne.

Chaque modification poussée sur GitHub redéploie tout seul.

## Résultat

```
/          accueil
/forum     le forum
/rms       la boutique
```

## Encore à faire (pas bloquant pour voir le site)

- Les trois pages du forum (/forum/sur, /forum/desaccord, /forum/inverifiable).
- Contact et mentions légales. **Les mentions légales sont obligatoires avant toute vente.**
- Aucun paiement n'est branché : les prix s'affichent, rien ne s'achète. Voulu.
- Vérifier le titre de l'affiche « Le salon, 1996 » (l'image est une cuisine).
