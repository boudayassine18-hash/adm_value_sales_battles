ADM VALUE OUJDA — SALES BATTLE (hors ligne)

CE ZIP N'EST PAS UN APK. Il contient le projet source et un workflow qui compile automatiquement l'APK sur GitHub Actions.

FONCTIONS
- Application Android plein écran en paysage, pensée pour Android TV / télécommande.
- Fonctionnement sans connexion Internet une fois installée.
- 6 équipes : ACHILLE, AFOU, GABY, YASSINE, ELYSÉE, SANDRINE.
- Compteurs indépendants FTTH, FAM et FSM avec + / -.
- Date modifiable, scores conservés localement par date.
- Totaux plateau et classement par total FTTH + FAM + FSM.
- Réinitialisation des compteurs de la date sélectionnée.

OBTENIR LE FICHIER APK AUTOMATIQUEMENT
1. Décompresser ce ZIP sur un ordinateur.
2. Créer un dépôt GitHub (privé ou public) et y importer tous les fichiers/dossiers du projet, y compris le dossier caché .github.
3. Dans GitHub, ouvrir l'onglet Actions et activer les workflows si GitHub le demande.
4. Lancer le workflow « Build ADM Value Sales Battle APK » avec le bouton Run workflow, ou faire un push sur main/master.
5. À la fin du workflow, ouvrir son exécution réussie, descendre à Artifacts et télécharger « ADM-Value-Sales-Battle-APK ».
6. Décompresser l'artefact : le fichier app-debug.apk est l'APK installable.
7. Copier app-debug.apk sur une clé USB, l'ouvrir depuis la TV Philips et autoriser l'installation depuis cette source si Android TV le demande.

PRÉREQUIS / LIMITES
- La compilation se fait sur les serveurs GitHub : Android SDK et Gradle sont installés automatiquement par le workflow.
- L'application n'a aucune permission Internet. Le réseau est nécessaire uniquement à GitHub pendant la compilation, pas sur la télévision après installation.
- L'APK debug est adapté à une installation de test locale. Il n'est pas publié sur le Play Store.
