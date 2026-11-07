# Fuckerman — version 4:3 de test v1

Copie séparée issue de `outputs/sauvegarde-2026-09-27/fuckerman-arcade-azerty.zip` du projet portable. L'original est conservé.

Le lanceur demande un rendu 4:3 au moteur Unreal (canvas et résolution réelle), avec conservation des proportions en plein écran. Aucun étirement CSS ajouté. Les données du jeu, le moteur compilé, les commandes F / R / 1 / & et le logo Patreon sont conservés. La caméra et les interfaces compilées peuvent néanmoins imposer leur propre cadrage : à vérifier en jeu.

## Essayer

Utiliser un hébergement HTTP(S) compatible WebAssembly/WebGL, comme pour la version actuelle. Ne pas lancer simplement index.html en double-cliquant. Pour garder la version actuelle accessible, placer cette version dans un dossier distinct du site, par exemple `test-4-3/`, ou dans un dépôt de test distinct. Le ZIP contient les fichiers directement à sa racine. Aucune publication n'a été effectuée.

Sur une surface média 800×600 ou 1024×768, le canvas doit occuper le cadre 4:3. Sur une surface 16:9, des bandes latérales restent normales. Vérifier aussi le cadrage intégré au jeu, qui peut conserver des bandes indépendantes du canvas.

Contrôler le menu et tous ses boutons, démarrer une partie, vérifier la vue, les indications, les déplacements, la visée, F pour tirer, R pour recharger, 1 / & pour sortir ou ranger le fusil, puis le retour au menu. Répéter dans Second Life après avoir donné le focus au média. Comparer avec l'ancienne version avant tout remplacement.

Dépendances : navigateur WebGL/WebAssembly, hébergement HTTP(S), accès aux CDN jQuery 2.1.3 et Bootstrap 3.3.4 déjà utilisés par l'original. Aucun outil de préparation nécessaire pour jouer.

Validation locale : syntaxe JavaScript et calcul de taille du vrai lanceur contrôlés séparément ; cela ne constitue pas une exécution complète du jeu ou une validation dans Second Life. Voir `travail/fuckerman-4-3-controles.json` dans le projet portable pour les mesures.