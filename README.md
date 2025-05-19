# MultiFlowCon

## 🚧 Projet en développement 🚧


## **Présentation**

Le projet **MultiFlowCon** a pour but de développer un **workflow automatisé** sous **n8n** permettant d’importer du contenu depuis plusieurs sources dans **Notion**, en respectant la structure native de chaque type de contenu.

Le système utilise les meilleures pratiques du développement de workflows et l’intégration avancée des API (Notion API, Google Drive, YouTube, OCR, etc.), ainsi que des agents IA pour enrichir l’importation et la transformation des données.

---

## **Objectifs**

- **Centraliser** des informations provenant de diverses sources dans Notion de manière automatique.
- **Simplifier** le traitement de contenus variés (textes, vidéos, fichiers) sans intervention manuelle.
- **Préserver** la structure originale et enrichir les données grâce à l’IA.
- **Optimiser** l’archivage et la documentation des ressources multimédia pour une gestion facilitée dans Notion.

---

## **Fonctionnalités principales**

- **Webpage to Notion** :
    - Scraping complet de pages web.
    - Conversion fidèle en blocs Notion (titres, paragraphes, images, listes…).
    - Conservation et correction des liens relatifs en absolus.
- **Fichiers vers Notion** :
    - Importation de contenus PDF, Markdown, XML, XLSX, TXT, images.
    - Extraction des données et traduction en structure Notion adaptée.
- **YouTube vers Notion** :
    - Embedding automatique de vidéos.
    - Importation de la description de la vidéo.
    - Génération d’un résumé complet du contenu vidéo via IA.
- **Gestion des API Notion** :
    - Support complet des opérations sur blocs, pages, bases de données, utilisateurs, commentaires, et recherche.
- **Configuration avancée** :
    - Authentification OAuth2 ou Token API pour Notion.
    - Connexions API supplémentaires (YouTube, OCR, Google Drive…).
    - Génération de titres automatique ou manuelle.
    - Menu de sélection du type de contenu et des opérations API à effectuer.
    - Stockage facultatif des images extraites dans Google Drive personnel.

---

## **Technologies utilisées**

- **n8n** : Automatisation du workflow.
- **Notion API** : Intégration de contenu.
- **Google Drive API** : Stockage d’images optionnel.
- **YouTube API** : Récupération de données vidéos.
- **Agents IA (MCP, RAG, mem0)** : Analyse et enrichissement du contenu.
