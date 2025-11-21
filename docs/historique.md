la commande que j'ai utiliséé ici c'est git log 

voici ce qui s'est affiché .

commit 2e446fc6e5f14b778c09ee91e5e1c1db7439f90c (HEAD -> dev, origin/dev)
Author: Shayton <ofomoisrael@gmail.com>
Date:   Fri Nov 21 17:08:20 2025 +0100

    suppréssion du fichier V8

commit 92f55f924cd1ab78a31a301b66dd6b69fdc1ffe6
Author: Shayton <ofomoisrael@gmail.com>
Date:   Fri Nov 21 17:07:07 2025 +0100

    fichier de l'exo 8 renomé

:



pour la différence de fichier j'ai utilisé git diff et voici ce qui s'est affiché :

diff --git a/README b/README
index ae65f16..7e1dba8 100644
--- a/README
+++ b/README
@@ -1 +1 @@
-Ce Dépot servira à vérifier nos travaux sur git hub et savoir si on a assimilé le tout.
\ No newline at end of file
+Ce Dépot servira à vérifier nos travaux sur git hub et savoir si on a assimilé le tout .
diff --git a/docs/exo7 b/docs/exo7
new file mode 100644
index 0000000..73814da
--- /dev/null
: