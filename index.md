# Présentation du repo _Klaro_ - Projet LINUX :
#### Benoit Grand et Jean-Julien Cordano - Février 2021 :

### Rappel des termes importants de github :
- **Branch :** Une branche ou *branch* est une version parallèle d'un référentiel (*repo*). Il est contenu dans le référentiel, mais n'affecte pas la branche principale, vous permettant de travailler librement sans perturber la version "live". Une fois que vous avez apporté les modifications que vous souhaitez apporter, vous pouvez fusionner votre branche dans la branche principale pour publier vos modifications.
- **Clone :** Un clone est une copie d'un référentiel qui vit sur votre ordinateur plutôt que sur le serveur d'un site Web quelque part, ou l'acte de faire cette copie. Lorsque vous effectuez un clone, vous pouvez modifier les fichiers dans votre éditeur préféré et utiliser Git pour suivre vos modifications sans avoir à être en ligne. Le référentiel cloné est toujours connecté à la version distante afin de pouvoir transmettre les modifications locales au repo en ligne.
- **Commit :** Un commit, ou «révision», est une modification individuelle d'un fichier (ou d'un ensemble de fichiers). Lorsque vous effectuez un commit pour sauvegarder votre travail, Git crée un identifiant unique (a.k.a. le "SHA" ou "hash") qui vous permet de garder une trace des modifications spécifiques validées.
- **Fetch :** Lorsque vous utilisez git fetch, vous ajoutez des modifications du référentiel distant à votre branche de travail locale sans les valider. Contrairement à git pull, la récupération vous permet de revoir les modifications avant de les appliquer dans votre branche locale.
- **Fork :** Un fork est une copie personnelle du référentiel (ou *repository*)d'un autre utilisateur qui réside sur votre compte. Les Forks vous permettent d'apporter librement des modifications à un projet sans affecter le référentiel amont d'origine. Vous pouvez également ouvrir une pull request dans le référentiel en amont et garder votre fork synchronisé avec les dernières modifications puisque les deux référentiels sont toujours connectés.
- **master :** La branche par défaut dans de nombreux référentiels Git. Par défaut, lorsque vous créez un nouveau référentiel Git sur la ligne de commande, une branche appelée master est créée.
- **merge :** La fusion prend les modifications d'une branche (dans le même référentiel ou d'un fork), et les applique dans une autre. Cela se produit souvent comme une "pull request" (qui peut être considérée comme une demande de fusion), ou via la ligne de commande. Une fusion peut être effectuée via un pull request via l'interface Web de GitHub.com s'il n'y a pas de modifications conflictuelles, et peuvent toujours être effectuée via la ligne de commande.
- **pull :** *Pull* fait référence au moment où vous récupérez des modifications et les fusionnez. Par exemple, si quelqu'un a modifié le fichier distant sur lequel vous travaillez tous les deux, vous souhaiterez intégrer ces modifications dans votre copie locale afin qu'elle soit à jour. Voir aussi fetch.
- **push :** *Push* ou pousser signifie envoyer vos modifications validées vers un référentiel distant sur GitHub.com. Par exemple, si vous modifiez quelque chose localement, vous pouvez appliquer ces modifications afin que d'autres puissent y accéder.

## Le repo Klaro :

Klaro est une librairie JavaScript open-source qui permet aux dévelopeurs de sites web de laisser choisir les visiteurs du site quels cookies accepter. 

Ce repo a été créé par kiproject le [26 mai 2018](https://api.github.com/repos/kiprotect/klaro), a été amélioré par 49 contributeurs, a été invoqué 19 fois et a été forké 161 fois. Un fork principale est [Orejime](https://github.com/empreinte-digitale/orejime) par l'utilisateur [empreinte-digitale](https://github.com/empreinte-digitale). Ce fork a été créé le [19 juillet 2018](https://api.github.com/repos/empreinte-digitale/orejime) et présente aujourd'hui des modules et une architecture différente.

### Points positifs :
- **Facile d'utilisation :** peut être ativé sur un site en seulement quelques lignes de code.
- **Gratuit et open-source :** cet outil ne requiert aucune souscription payante. Par ailleurs, une page [Issues](https://github.com/KIProtect/klaro/issues) est mise en avant sur le repo original pour encourager la collaboration et l'amélioration constante de l'outil.
- **Securisé :** klaro assure qu'aucun cookie ou tracker de tiers ne s'executent sans le consentement de l'utilisateurs, même lorsque JavaScript est désactivé ou klaro est bloqué. 
- **Flexible and personalisable :** klaro peut être modifié et personnalisé pour des cookies tiers de natures différentes, dépendamment des besoins.
- **Multilingue :** klaro est disponible en 18 langues actuellement et d'autres peuvent être ajoutés par les contributeurs.
- **Intuitif :** klaro est développé pour s'accorder à l'apparence de tout site internet, aussi bien sur ordinateur ou smartphone.
- **Complet :** [Site internet](https://kiprotect.com/klaro) exhaustif et professionel.

### Améliorations possibles :
- **Manque de tutoriels :** bien que facile à activer, aucuns cas d'usages ou d'exemples d'utilisation de klaro sont présentés sur le repo.  Cela pourrait être bénéfique pour encourager son utilisation.
