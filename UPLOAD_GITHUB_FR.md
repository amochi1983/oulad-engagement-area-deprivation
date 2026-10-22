# Téléverser le dépôt sur GitHub

Auteur du logiciel : **Aymen Ochi**. Le dossier est prêt à être importé ; aucune publication automatique n'a été effectuée.

## 1. Extraire l'archive

Extraire OULAD_GitHub_Aymen_Ochi_2026-10-22.zip. Le dossier oulad-engagement-area-deprivation contient README.md,LICENSE,AUTHORS.md,CITATION.cff,src,tests,data,outputs et les autres fichiers scientifiques.

Ne téléversez pas uniquement le ZIP : publiez son **contenu**,avec README.md directement à la racine du dépôt GitHub. Les fichiers bruts OULAD sont obtenus ensuite par la procédure de téléchargement ; ils n'ont pas à être ajoutés à Git.

## 2. Créer un dépôt vide

Sur votre compte GitHub,créer un dépôt nommé par exemple **oulad-engagement-area-deprivation**. Choisir la visibilité souhaitée pour le partage public prévu. Ne pas générer un secondREADME,une seconde licence ou un autre.gitignore : les fichiers corrects sont déjà fournis.

## 3. Publier les fichiers

GitHub Desktop ou Git permettent de publier l'ensemble du dossier sans découper l'envoi par lots. Si vous utilisez Git dans le dossier extrait et un dépôt distant vide,les commandes suivantes configurent l'auteur **localement**,pour ce seul dépôt :

```powershell
git init -b main
git config user.name "Aymen Ochi"
git config user.email "amochi@uhb.edu.sa"
git add .
git commit -m "Initial release of OULAD analysis code"
```

Configurer ensuite le dépôt distant avec **la véritableURLde votre dépôt**,puis pousser :

```powershell
git remote add origin https://github.com/VOTRE_COMPTE/oulad-engagement-area-deprivation.git
git push -u origin main
```

Remplacer VOTRE_COMPTE par votre identifiant ; ce texte d'instruction n'est pas une déclaration d'accessibilité publique. GitHub peut demander votre authentification. Ne partagez aucun mot de passe ou jeton dans le dépôt ou dans le chat. Les commandes ne suppriment pas de fichiers et ne réécrivent pas un historique existant ; elles supposent un nouveau dépôt vide.

Si vous préférez Add file > Upload files dans le navigateur,GitHub limite un envoi à100fichiers et25MiBpar fichier. Aucun fichier de cette archive n'excède25MiB,mais le dépôt complet dépasse100fichiers : répartir les envois en conservant les chemins,ou utiliser GitHub Desktop/Git. Le dossieroutputscontient plusieurs sous-dossiers et ne doit pas être aplati. Documentation officielle vérifiée le22octobre2026 : https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository .

## 4. Vérifier après téléversement

- README.md s'affiche à la racine.
- LICENSE afficheMITavecAymenOchi,etCITATION.cff citeAymenOchi.
- DATA_LICENSE.md attribueOULADàKuzilek,HlostaetZdrahal,sousCCBY4.0.
- Les dossierssrc,tests,configs,data/processed,reference_tables etoutputs sont présents.
- Aucun dossier.git,aucune.venv,aucun fichier brutstudentVle.csv ni archiveanonymisedData.zip n'ont été publiés.
- AUTHORS.md conserve les contributions scientifiques d'Abdullah Muzil Alharbi ;AI_ASSISTANCE.md reste une divulgation distincte,non une attribution d'auteur.

Renvoyer ensuite l'URLréelledu dépôt pour l'intégrer au manuscrit lors de la mise à jour finale. Le dépôt de code peut être prêt au partage alors que la justification éthique et l'approbation du manuscrit final restent à finaliser. Aucune approbation institutionnelle n'est inventée.
