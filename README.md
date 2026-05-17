# 📋 BEP & Charte BIM — Skill Claude AI

> **Premier skill Claude AI open source dédié au BIM au Maghreb**  
> Rédige automatiquement des BEP (BIM Execution Plan) et Chartes BIM  
> conformes ISO 19650, en français, adaptés au marché algérien.

---

## 🚀 Ce que fait ce skill

Ce skill permet à **Claude AI** de rédiger des documents BIM professionnels :

| Document | Description |
|---|---|
| **BEP** (BIM Execution Plan) | Plan d'exécution BIM complet pour un projet |
| **Charte BIM** | Document cadre BIM pour une entreprise |

### ✅ Points forts
- Conformité **ISO 19650-1 et ISO 19650-2**
- Adapté au **marché Maghreb / Algérie** (phases françaises, contexte local)
- Intègre les **conventions BSO_** (paramètres Revit partagés BIM-SOLLUTIONS)
- Livrable en **Word (.docx)** ou aperçu direct dans Claude
- Structure complète : rôles RACI, LOD, CDE, MIDP, matrice des échanges

---

## 📦 Structure du skill

```
bep-charte-bim/
├── SKILL.md                              ← Skill principal (instructions Claude)
├── README.md                             ← Ce fichier
└── references/
    ├── bep-template.md                   ← Template BEP complet (12 sections)
    ├── charte-bim-template.md            ← Template Charte BIM (9 sections)
    └── conventions-bim-sollutions.md     ← Standards BSO_ et conventions
```

---

## 🛠️ Installation

### Option 1 — Claude.ai (interface web)
1. Allez dans **Settings > Skills**
2. Cliquez **Add skill**
3. Uploadez le dossier `bep-charte-bim/`

### Option 2 — Claude Code (terminal)
```bash
git clone https://github.com/BIM-SOLLUTIONS/bep-charte-bim-skill.git
cp -r bep-charte-bim-skill ~/.claude/skills/bep-charte-bim
```

---

## 💬 Comment utiliser

Une fois installé, tapez dans Claude :

```
Rédige un BEP BIM pour mon projet hôtel 5 étoiles à Alger, 
15 étages, 200 chambres. Maître d'ouvrage : Groupe SARL Horizon.
Logiciels : Revit 2024 + ACC.
```

ou

```
Crée une charte BIM pour mon bureau d'études architecture, 
15 collaborateurs, projets résidentiels et commerciaux en Algérie.
```

---

## 📋 Contenu du BEP généré

1. ✅ Informations générales du projet
2. ✅ Objectifs et usages BIM (tableau)
3. ✅ Rôles et responsabilités RACI
4. ✅ Plan de livraison MIDP
5. ✅ Niveaux d'information LOD 100→500
6. ✅ Environnement de données commun (CDE)
7. ✅ Conventions de nommage ISO 19650
8. ✅ Processus de coordination et clash
9. ✅ Planning des jalons BIM
10. ✅ Matrice des échanges d'information
11. ✅ Exigences logicielles et formats IFC
12. ✅ Contrôle qualité et checklist

---

## 🏢 À propos de BIM-SOLLUTIONS

**BIM-SOLLUTIONS** est une entreprise algérienne spécialisée en :
- BIM Management et coordination
- Formation Revit et BIM (ISO 19650, CDE, Dynamo)
- Développement de plugins Revit
- Workflows BIM+IA (Claude AI + Revit MCP)
- Consulting ISO 19650 et ACC

🌐 [bim-solution-dz.com](https://bim-solution-dz.com)  
📧 modelisation@bim-solution-dz.com  
📧 formation@bim-solution-dz.com

---

## 📄 Licence

**MIT License** — Libre d'utilisation, modification et redistribution.  
Merci de mentionner **BIM-SOLLUTIONS** comme source.

---

## ⭐ Contribuer

Les contributions sont les bienvenues !
- Ajouter des templates pour d'autres types de projets
- Traduire en arabe / anglais
- Ajouter des templates pour d'autres marchés (Maroc, Tunisie, France)

**Ouvrez une issue ou une pull request sur GitHub.**

---

*Développé par **Ouafek Mahizi** — BIM Manager & Consultant*  
*BIM-SOLLUTIONS | Alger, Algérie*
