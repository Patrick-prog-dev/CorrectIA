# CorrectIA

**CorrectIA** est un agent d'Intelligence Artificielle révolutionnaire conçu pour automatiser l'évaluation sémantique et la correction des examens de masse, tout en maintenant l'enseignant au centre du processus (*Human-in-the-loop*). 

Contrairement aux systèmes d'évaluation automatique traditionnels souvent limités aux Questionnaires à Choix Multiples (QCM), **CorrectIA s'attaque aux questions ouvertes à réponses courtes, rédigées à la main par des étudiants en conditions réelles d'examen.**

---

## Performances & Métriques Clés

Validé académiquement lors d'une soutenance de Master 2 IA & BD (Pigier Bénin, Juin 2026) et présenté internationalement à la conférence **ETECOM 2026**, CorrectIA a démontré des métriques d'alignement industriel et scientifique exceptionnelles sur un jeu de données de copies manuscrites réelles :

*   **κ = 0,869 (Kappa de Cohen) :** Accord quasi-parfait entre l'agent IA et le correcteur humain, prouvant une haute fidélité dans la compréhension sémantique des réponses libres courtes.
*   **ICC = 0,874 (Coefficient de Corrélation Intraclasse) :** Excellente fiabilité inter-juges absolue.
*   **MAE = 1,14 (Erreur Absolue Moyenne) :** Un écart type moyen restreint à seulement ~1,14 point sur une échelle de 20 par rapport à la notation humaine stricte.
*   **95% de Validation Directe :** Grâce à l'approche collaborative, l'enseignant valide la note et le feedback sémantique proposés par l'IA en un seul clic dans 95% des cas.
*   **Gain de temps de ×38 :** Permet la numérisation, la transcription et la notation fluide de plus de **1 000 copies d'examen par jour**, soulageant drastiquement la charge administrative des correcteurs.

---

## Architecture du Système

CorrectIA s'appuie sur un pipeline hybride combinant la Vision par Ordinateur (Computer Vision) et le Traitement du Langage Naturel (NLP) :

1.  **Pipeline HTR/OCR (Vision) :** Segmentation de l'image de la copie manuscrite, redressement des lignes, et extraction du texte manuscrit brut à l'aide de modèles de Reconnaissance de Texte Manuscrit (Handwritten Text Recognition) optimisés pour l'écriture en conditions de stress (examens réels).
2.  **Moteur d'Analyse Sémantique (NLP) :** Intégration de modèles de langage spécialisés, ajustés (*fine-tuned*) pour l'évaluation sémantique comparative. Le système analyse la substance de la réponse courte de l'étudiant par rapport au barème et aux critères du professeur, ignorant les variations orthographiques non pénalisantes pour se concentrer sur l'exactitude du concept.
3.  **Interface Human-in-the-loop (HITL) :** Tableau de bord ergonomique permettant à l'enseignant de superviser les annotations de l'IA, de modifier une note à tout moment, et d'apprendre des corrections manuelles pour affiner les futures prédictions.

---

## Validation Scientifique

*   **Juin 2026 :** Soutenance de Master 2 en Intelligence Artificielle et Big Data (IA & BD).
*   **2026 :** Acceptation, publication et présentation de l'article de recherche détaillant l'architecture sémantique de CorrectIA à la conférence internationale *ETECOM 2026 (International Conference on Emerging Trends in Engineering and Computing)*.

---

## Perspectives & Passage à l'Échelle (Scaling)

Dans le cadre du développement du projet au sein de l'écosystème d'innovation à Cotonou (Bénin), les prochaines étapes techniques incluent :
*   L'optimisation du modèle d'OCR pour la gestion des copies fortement dégradées ou raturées.
*   L'adaptation sémantique aux spécificités contextuelles et expressions locales de l'écosystème éducatif ouest-africain.
*   Le déploiement d'une architecture cloud distribuée pour supporter les flux des examens nationaux.

---

## Auteur

**Malick Patrick Sétondé Gbetoho**  

## Co auteurs

**Dr Lionel AFFOGNON**

**Dr Hervé B. Olou**

**Pr Eugène C. Ezin**

*Ingénieur IA & NLP | Concepteur EdTech*  
malickgbetoho@gmail.com | www.linkedin.com/in/malick-gbetoho-2477bb1a4
