# 🕸️ R05 - Fake Webpage (Phishing Simulation)

> Projet de simulation de site web malveillant dans un cadre pédagogique et sécurisé en cybersécurité.

## 🎯 Objectif

Ce projet a pour but de **simuler un site web de phishing** dans un environnement contrôlé dans le cadre de répondre à l'annexe R05 sur l'analyse des malwares. Il s'agit ici de jouer sur l'ingénierie social pour montré qu'il est assez simple de duper les personnes non préparé.

> [!CAUTION] Attention
>  **Ce projet ne doit jamais être utilisé à des fins illégales. Il a été créé exclusivement à des fins pédagogiques uniquement**

## 📂 Structure du projet

| Fichier | Description                                                          |
| --------------- | -------------------------------------------------------------------- |
| `index.html`    | Page d’accueil simulant la présentation du produit                   |
| `page-lois.html`     | Un rappel sur les lois du code-pénale |
| `NeuroSphere-setup.exe`     | Le Trojan absent ici pour des raisons évidente de sécurité                       |

## ⚙️ Fonctionnement

1. **L’utilisateur accède à `index.html`** via un navigateur.
2. **Une fausse publicité pour un produit** est affichée.
3. **Si intéréssé l'utilisateur suivra à la lettre les recommandations** (ingénierie social).
4. Lors du téléchargement il sera demandé de :
    - Désactiver `antivirus`.
    - Désactiver `pare-feu`.
5. Après exécution du programme, rien ne se passe.

> [!WARNING] Important
> **A cet instant, `le poste est contrôlé par un pirate dans que l'utilisateur ne le sache`.**

## Impacts possibles

-   Capture d'écran
-   Capture des touches du clavier
-   Elévation des privilèges
-   Navigation sur le système
-   Exfiltration de document en tout genre

