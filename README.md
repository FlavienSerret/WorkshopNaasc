## 📁 README – Rapports de Diagnostic et d'Erreur CU

Ce dossier contient les **modèles de documents** à utiliser pour le **suivi technique** des charges utiles CU (Charge Utile), que ce soit en routine ou en cas d’anomalie.

---

### 📌 Objectif

Les documents permettent de :
- **Documenter les analyses techniques** (dossier `rapport_d'analyse/`)
- **Formaliser les erreurs ou incidents détectés**, leur impact et les mesures urgentes à prendre (dossier `rapport_d'erreur/`)

Cela garantit un **suivi rigoureux, standardisé et traçable** du comportement des charges utiles.

---

### 🗂️ Arborescence des dossiers

charges_utile/
├── rapport_d'analyse/
│ └── Rapport_d'analyse_Template_CU.docx
├── rapport_d'erreur/
│ └── Rapport_d'erreur_Template_CU.docx
└── README.md


---

### 📝 Instructions d'utilisation

#### 1. Choisir le bon modèle
- 📊 Analyse sans anomalie critique → `rapport_d'analyse/Rapport_d'analyse_Template_CU.docx`
- ⚠️ Anomalie détectée → `rapport_d'erreur/Rapport_d'erreur_Template_CU.docx`

#### 2. Compléter le rapport
- Renseigner **date, expert, données analysées, comportement ou anomalie, recommandations**
- Ajouter les **graphiques d’analyse** si nécessaire

#### 3. Exporter en PDF
- Nommer le fichier de manière claire :
  - `CU[Numéro]_Rapport_Analyse_[Date].pdf`
  - `CU[Numéro]_Erreur_[Date].pdf`

#### 4. Déclaration d’une erreur
En cas d’erreur détectée :
- Remplir un rapport d’erreur (voir ci-dessus)
- **Créer une *issue* dans l’espace de suivi** pour notifier le problème et joindre le rapport PDF
- Notifier le superviseur concerné

---

### 📣 Bonnes pratiques

- Toujours **archiver** le PDF dans le système documentaire une fois validé
- Respecter le format des rapports pour une homogénéité dans le suivi
- En cas de doute ou de changement de procédure, **consulter le référent**

---

