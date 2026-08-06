# Releases — Outils CLEVA

Distribution des releases des outils internes ALPTIS.

---
## Tableau de bord

| Outil | Dernière version | Lien |
|-------|------------------|------|
| plan-batch | v1.0.4 | [Télécharger](https://github.com/zomeno/alptis-releases/releases/tag/v1.0.4) |
| param-compare | v1.0.0 | [Télécharger](https://github.com/zomeno/alptis-releases/releases/tag/param-compare-v1.0.0) |
| find-my-log | v1.2.0 | [Télécharger](https://github.com/zomeno/alptis-releases/releases/tag/find-my-log-v1.2.0) |
| analyse-log-api | v1.0.0 | [Télécharger](https://github.com/zomeno/alptis-releases/releases/tag/analyse-log-api-v1.0.0) |
| cleva-anonymisation | v1.0.0 | [Télécharger](https://github.com/zomeno/alptis-releases/releases/tag/cleva-anonymisation-v1.0.0) |
| tnr-batch-copie-fichier | v1.0.0 | [Télécharger](https://github.com/zomeno/alptis-releases/releases/tag/tnr-batch-copie-fichier-v1.0.0) |

---
## Plan Batch

> Visualisation interactive des chanes de traitements batch — vue fonctionnelle, technique et OpCon.

**Fonctionnalités :**
- Vue macro (graphe des chanes métier) et vue détail (jobs d'une chane)
- 3 modes d'affichage : Fonctionnel / Technique / Exploitation (OpCon)
- Synchronisation automatique avec un dépt git de données (YAML)
- Interface web locale embarquée dans un installeur Windows (Electron)
- Push git automatique des modifications (toutes les N minutes ou via bouton dédié)

**Dernière version :**
[v1.0.3](https://github.com/zomeno/alptis-releases/releases/tag/v1.0.3)

---
## Param Compare

> Comparaison croisée des paramètres entre environnements CLEVA.

**Fonctionnalités :**
- Interface Streamlit portable (PyInstaller), sans installation requise
- Comparaison de paramètres entre environnements (recette, prod, etc.)
- Simulation d'import et attente active du fichier résultat SMB

**Dernière version :**
[v1.0.0](https://github.com/zomeno/alptis-releases/releases/tag/param-compare-v1.0.0)

---
## Find-My-Log

> Navigateur de logs CLEVA K8s — outil graphique Windows sans dépendances.

**Fonctionnalités :**
- Identification des pods actifs sur une période (Du / Au facultatif)
- Navigation dans les fichiers de log (courants .log et archives .gz)
- Recherche dans le contenu (F3 / Shift+F3)
- Recherche plein fichier et multi-pods en streaming, résultats cliquables façon Notepad++
- Décompression .gz à la volée, ouverture dans Notepad / Explorateur
- Interface WPF native Windows, aucun runtime requis (PowerShell 5.1+)

**Dernière version :**
[v1.2.0](https://github.com/zomeno/alptis-releases/releases/tag/find-my-log-v1.2.0)

---
## CLEVA Anonymisation

> Anonymisation RGPD de la base de données CLEVA — interface Streamlit locale, sans outil Oracle externe.

**Fonctionnalités :**
- Remplacement des données personnelles (noms, prénoms, adresses, IBAN) par des valeurs fictives
- Dictionnaires de substitution basés sur des données INSEE réelles (218 983 noms, prénoms, adresses)
- Lanceur graphique Windows (Tkinter) avec indicateur d'état Start/Stop
- Interface Streamlit accessible sur http://localhost:8501
- Connexion Oracle sécurisée (mot de passe jamais stocké sur disque)

**Dernière version :**
[v1.0.0](https://github.com/zomeno/alptis-releases/releases/tag/cleva-anonymisation-v1.0.0)

---
## purge-fs

> Gestion de purge et d'archivage de fichiers sur partages réseau — interface graphique Windows et CLI.

**Fonctionnalités :**
- Interface graphique PyQt6 (onglets Scan, Analyse, Purge, Suivi)
- Scan multithreadé des partages réseau avec pause/stop
- Analyse des répertoires et suggestion de règles de purge
- Purge et archivage des fichiers selon règles de rétention configurables
- Support CLI complet (`purge-fs.py scan / analyse / purge`)
- Distribution portable (PyInstaller), aucune installation requise

**Dernière version :**
[v1.0.0](https://github.com/zomeno/alptis-releases/releases/tag/purge-fs-v1.0.0)

---

## Analyse Log API

> Analyse des logs d'accès API CLEVA pour mesurer les usages par utilisateur, endpoint et période.

**Fonctionnalités :**
- Analyse des fichiers cleva_access* (.log, .gz, .zip)
- Agrégation par utilisateur / endpoint / méthode
- Interface GUI (Tkinter) avec filtres, tri et export CSV
- Mode script batch pour traitement automatisé

**Dernière version :**
[analyse-log-api-v1.0.0](https://github.com/zomeno/alptis-releases/releases/tag/analyse-log-api-v1.0.0)

---
## TNR Batch Copie Fichier

> Copie contrôlée de fichiers batch entre environnements CLEVA via jeux de règles INI.

**Fonctionnalités :**
- Interface WPF pour créer, éditer et exécuter des jeux de règles
- Sélection des N fichiers les plus récents (masque + extension)
- Gestion multi-jeux de règles avec commentaires
- Test des répertoires source/cible avant copie
- Démarrage simplifié via lanceur Windows (lancement-copie.vbs)

**Dernière version :**
[tnr-batch-copie-fichier-v1.0.0](https://github.com/zomeno/alptis-releases/releases/tag/tnr-batch-copie-fichier-v1.0.0)
