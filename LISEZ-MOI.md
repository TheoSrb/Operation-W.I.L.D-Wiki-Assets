# Operation W.I.L.D — assets du wiki

Les images, sons et modeles du wiki (https://operation-wild-wiki.netlify.app).
Le site les demande a `assets/...` ; Netlify va les chercher ici, via GitHub Pages.

**Ce dossier est mis a jour par le mod** : dans IntelliJ, `Operation-W.I.L.D [runWikiDatas]`.
La tache regenere le JSON du wiki et recopie ici tout ce qui vient du mod (textures,
sons, musiques, modeles 3D) et du dossier `Operation W.I.L.D` du Bureau (wallpapers,
logo, theme principal), puis refait les vignettes, apercus et inventaire.

A deposer a la main (rien ne les produit automatiquement) :
- `entities/`, `entities/solo/`, `heads/` : les rendus des betes ;
- `pages/<bete>/` : variantes (`<bete>_0.png`...), skins (`skin_0.png`...), GIF
  (`anim_0.gif`...), captures (`gallery_0.png`...), cartes d'attaque, selle ;
- `skins/` : rendus et modeles 3D (glTF) des cosmetiques ;
- `mcitems/`, `mcblocks/` : les textures de Minecraft, aux noms du jeu.

Ne jamais y mettre ce qui doit rester secret : ce depot est public, historique compris.
Pour que le site les trouve : depot **public**, et GitHub Pages active
(Settings > Pages > Deploy from a branch > main, dossier / (root)).
