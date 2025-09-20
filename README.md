# 📊 A/B Testing Algorithm

## 📝 Description
L’A/B Testing est une stratégie essentielle de marketing utilisée dans tous les business en ligne pour déterminer :  
- si une innovation mérite d’être implémentée définitivement,  
- ou si une version d’un produit est préférée à une autre par les clients.  

Le principe est simple :  
- Deux versions d’un produit (**A** et **B**) sont proposées à deux échantillons distincts d’individus.  
- Chaque individu fait un choix : conserver le produit ou le rejeter.  
- On compare ensuite les proportions de conservation entre les deux groupes pour évaluer la version la plus performante.  

Ce projet vise à **modéliser, estimer et comparer ces proportions** afin de définir une **règle de décision statistique efficace** pour choisir la meilleure version.  

---

## 🎯 Objectifs du projet
1. **Estimation des proportions**  
   - Obtenir des estimations précises des taux de conservation dans chaque groupe.  
   - Garantir que les comparaisons ne soient pas biaisées.  

2. **Décision statistique**  
   - Déterminer une règle de décision fiable pour comparer les deux proportions.  
   - Identifier si la version A ou B est significativement meilleure.  

3. **Application concrète**  
   - Étude de cas détaillée, disponible dans un **notebook** en annexe (📎 A.2).  

---

## 📂 Contenu du dépôt
- `notebooks/` → notebooks d’analyse statistique et d’application pratique.  
- `pdf/` → compte rendu complet du projet.
- `README.md` → ce fichier de présentation du projet.  

---

## ⚙️ Méthodologie
- Échantillonnage et simulation de données.  
- Estimation statistique des proportions.  
- Utilisation d’inégalités de concentration (Bienaymé-Tchebychev, Hoeffding, Bernstein, etc.) pour garantir la précision.  
- Construction d’une règle de décision optimale.  
