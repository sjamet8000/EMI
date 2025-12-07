# Définition et contexte

L’AI Act est la première grande **réglementation européenne** visant à encadrer l’usage et la mise sur le marché des systèmes d’IA.
L’objectif déclaré : protéger les droits fondamentaux, la sécurité, la santé, tout en permettant l’innovation, par un cadre commun, harmonisé dans l’UE.
Il adopte une approche fondée sur **le risque** : selon que l’IA soit “à risque inacceptable”, “haut risque (high-risk)”, “usage général (general-purpose)” ou “risque limité/faible”.

Ca concerne :
- **Fournisseurs, développeurs, importateurs ou distributeurs** de systèmes IA.
- **Tous les systèmes mis sur le marché ou utilisés dans l’UE**, même s’ils ont été développés ailleurs (effet extraterritorial).
Avec une attention particulière aux **systèmes “haut risque”** : santé, justice, éducation, emploi, infrastructures critiques, etc., avec documentation et contrôles renforcés.

Quelques dates :
**12 juillet 2024** : Publication officielle de l’AI Act au Journal officiel de l’Union Européenne. ([artificialintelligenceact.eu](https://artificialintelligenceact.eu))
**1er août 2024** : Entrée en vigueur formelle de l’AI Act, le texte est validé, mais les obligations ne s’appliquent pas encore globalement.
Ensuite, l’entrée en vigueur de certaines dispositions de l’IA Act s’échelonnent entre le 2 février 2025 et le 2 août 2027 pour la réglementation de certains produits.

![Pasted image 20251126080834.png](Pasted%20image%2020251126080834.png)

---

# Les différentes catégories de risque

Cf. [Résumé de haut niveau de la loi sur l'IA](https://artificialintelligenceact.eu/fr/high-level-summary/) et pour le texte complet, c'est [ici](https://artificialintelligenceact.eu/fr/ai-act-explorer/)

**1. Faible niveau de risque à risque minimal :**
IA à « risque limité » (chatbots, deepfakes non ciblés, outils de génération) ne sont pas interdits ni soumis à des lourdes obligations, mais peuvent entraîner **obligations de transparence** (ex. informer l’utilisateur qu’il interagit avec une IA).
Les systèmes « minimal risk » n’ont quasiment pas d’exigences.
Exemple : les chatbots

**2. Haut risque :**
Les systèmes d’IA dont l’utilisation peut affecter la sécurité, la santé ou les droits fondamentaux (ex. emploi, crédit, éducation, santé, justice, police) sont autorisés mais soumis à obligations strictes (gestion des risques, gestion des données, documentation techniques, évaluation de conformité, registres, audits).

**3. Risque inacceptable :**
Pratiques d’IA qui portent atteinte aux droits fondamentaux ou à la dignité humaine et sont donc prohibées (ex. « social scoring », manipulation cognitive ciblée, identification biométrique en temps réel sur des foules) ; exceptions très limitées.
Exemple : **Scraping massif d’images faciales + reconnaissance biométrique ([Clearview AI](https://www.clearview.ai/))**
Exemple : des systèmes d'IA fait pour le **recrutement et le tri de CV** sont interdits par l'IA Act, cf. [Insight - Amazon scraps secret AI recruiting tool that showed bias against women](https://www.reuters.com/article/world/insight-amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK0AG/)

![IA_ACT_clearview.png](IA_ACT_clearview.png)
![Pasted image 20251124212903.png](Pasted%20image%2020251124212903.png)
![IA_ACT_High_risk.png](IA_ACT_High_risk.png)

![Pasted image 20251129174733.png](Pasted%20image%2020251129174733.png)

---

# Les obligations des fournisseurs

**1. Evaluation de conformité :**
L’évaluation de conformité est réalisée **par le fournisseur** lui-même ou par un **organisme certifié indépendant**, selon le type de système.
Pour les **systèmes à haut risque “standard”** (Annexe III), le fournisseur peut suivre une **auto-évaluation** basée sur un système de gestion des risques, sauf exceptions.
Pour certains systèmes à impact critique, la conformité doit être validée par un **organisme certifié**, cf. [art. 43.](https://artificialintelligenceact.eu/fr/article/43/)

![IA_ACT_art_43.png](IA_ACT_art_43.png)

**2. La documentation technique doit contenir :**
- description du système, finalité, architecture générale ;
- description des données d’entraînement (origine, caractéristiques, prétraitement) ;
- méthodes d’évaluation, métriques de performance, limites connues ;
- mesures de gestion des risques ;
- procédures de surveillance humaine ;
- notes sur la cybersécurité ;
- documentation d’usage et instructions.
Cf. [Annexe IV](https://artificialintelligenceact.eu/fr/annex/4/)

![IA_ACT_doc_tech_annexe_IV.png](IA_ACT_doc_tech_annexe_IV.png)

Le code source n'est jamais exigé.

**3. Mécanisme de gestion des risques**
Les fournisseurs doivent prévoir des moyens :
- d’isoler une fonctionnalité,
- de désactiver un module,
- ou de retirer temporairement le système du marché.

Cf. [Article 9](https://artificialintelligenceact.eu/fr/article/9/)

![IA_ACT_Art.9.png](IA_ACT_Art.9.png)

SINON

Sanction :
- des amendes calculées sur le montant du chiffre d'affaire mondial, en fonction de la gravité de la faute
- et si un système qui a été mis sur le marché présente tout de même un risque grave, il peut être **physiquement empêché d'être utilisé en UE**

Cf. [Article 99](https://artificialintelligenceact.eu/fr/article/99/)

![AI_ACT_art_99.png](AI_ACT_art_99.png)

![Pasted image 20251129174715.png](Pasted%20image%2020251129174715.png)
![Pasted image 20251129175337.png](Pasted%20image%2020251129175337.png)

---
Si vous avez besoin d’ajustements ou d’une version adaptée pour un usage spécifique, n’hésitez pas à me le préciser.