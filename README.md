# TPICT314_YANGO_NGANYOU_GESLIE_SORELLE_25I2171

# RESUME: Investigation Numérique avec Autopsy

---

##  Introduction
Autopsy est une plateforme d'investigation numérique "open source" utilisée pour analyser les disques durs, les smartphones et les supports de stockage. 

---

##  Procédure Pas à Pas

### 1. Initialisation de l'Enquête
* **Lancer Autopsy** (en mode Administrateur sous Windows).
* Cliquer sur **"New Case"**.
* Renseigner le nom du cas (ex: `Analyse_Sûreté_01`) et le répertoire de stockage.
* Ajouter les informations optionnelles (Numéro du cas, nom de l'examinateur).

### 2. Importation de la Source de Données
* Cliquer sur **"Add Data Source"**.
* **Sélection du type :** Choisir `Local Disk` (pour une clé USB branchée) ou `Disk Image` (pour un fichier .E01 ou .img).
* Sélectionner le lecteur cible et cliquer sur **"Next"**.

### 3. Configuration de l'Analyse (Ingest Modules)
Pour une recherche efficace, j'ai activé les modules suivants :
* **File Type Identification :** Pour identifier les fichiers par leur signature réelle et non leur extension.
* **Keyword Search :** Pour indexer le texte et rechercher des mots-clés.
* **Recent Activity :** Pour extraire l'historique web et les activités récentes de l'OS.
* **Extension Mismatch Detector :** Pour repérer les fichiers cachés (ex: un .exe renommé en .jpg).

### 4. Analyse et Investigation
Une fois l'analyse lancée, j'ai exploré les sections suivantes dans la colonne de gauche :
* **Deleted Files :** Pour visualiser et restaurer les fichiers supprimés.
* **File Types :** Pour filtrer les résultats par types (Images, Vidéos, Documents).
* **Geolocation :** Pour extraire les coordonnées GPS des photos trouvées sur le support.

### 5. Génération du Rapport Final
* Cliquer sur l'icône **"Generate Report"**.
* Sélectionner le format **"HTML Report"**.
* Consulter le fichier `index.html` généré dans le dossier du cas pour voir la synthèse des preuves marquées.

  ## CONCLUSION
  Durant ce test j'ai pu comprendre et apprendre comment extraires ou récupéerer des données  supprimées .





**Geslie Sorelle Yang Nganyou** Étudiante en Bachelor ICT (Information and Communication Technology)
