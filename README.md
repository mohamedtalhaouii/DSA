# **Plan du Contenu**
### **1- Algorithmes**

- **[Algorithmes de Tri :](#algorithmes-de-tri-)**

  - **[Tri par Sélection (Selection Sort)](#1-tri-par-sélection-selection-sort)**
  - **[Tri par Insertion (Insertion Sort)](#2-tri-par-insertion-insertion-sort)**
  - **[Tri à Bulles (Bubble Sort)](#3-tri-à-bulles-bubble-sort)**
  - **[Tri Fusion (Merge Sort)](#4-tri-fusion-merge-sort)**
  - **[Tri Rapide (Quick Sort)](#5-tri-rapide-quick-sort)**
  - **[Tri par Tas (Heap Sort)](#6-tri-par-tas-heap-sort)**

- **[Algorithmes de Recherche :](#algorithmes-de-recherche-)**

  - **[Recherche Séquentielle (Linear Search)](#1-recherche-séquentielle-linear-search)**
  - **[Recherche Dichotomique (Binary Search)](#2-recherche-dichotomique-binary-search)**

- **[Complexité :](#complexité-)**

  - **[Notation Big O](#notation-big-o)**
  - **[Complexité Temporelle](#complexité-temporelle-)**
  - **[Complexité Spatiale](#complexité-spatiale-)**
  - **[Analyse de la Complexité](#analyse-de-la-complexité-)**
  - **[Importance de la Complexité](#importance-de-la-complexité-)**
  - **[Techniques pour Réduire la Complexité](#techniques-pour-réduire-la-complexité-)**

---

### **2- Structures de Données**

---

### **3- Navigation Rapide**
- [Algorithmes](#algorithmes)  
- [Structures de Données](#structures-de-données)  

---

# **1- Algorithmes :**
### **[🔝 Retour à l'index](#plan-du-contenu)**

## **Algorithmes de Tri :**

![SortingAlgorithms](https://github.com/user-attachments/assets/fcc85d4a-6b51-47ab-af19-55aa6e5acdc4)

Cliquez sur les liens pour explorer les implémentations de chaque algorithme dans le dossier GitHub.

### 1. **[Tri par Sélection (Selection Sort)](https://github.com/mohamedtalhaouii/DSA/tree/60a1abcb85d3f3789b55baffd68a37738609b97c/Algorithmes/Tri%20(Sort)/1-%20Selection)**  
   - Complexité : **O(n²)** (tous les cas).  
   - Trouve le plus petit élément et le place au début.  

### 2. **[Tri par Insertion (Insertion Sort)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Tri%20(Sort)/2-%20insertion)**

   - Complexité : **O(n²)** (cas moyen et pire), **O(n)** (meilleur cas).  
   - Insère chaque élément à sa place dans une liste triée.  


### 3. **[Tri à Bulles (Bubble Sort)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Tri%20(Sort)/3-%20Bulles)**  
   - Complexité : **O(n²)** (cas moyen et pire), **O(n)** (meilleur cas).  
   - Compare et échange des éléments adjacents.

### 4. **[Tri Fusion (Merge Sort)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Tri%20(Sort)/4-%20Fusion)**  
   - Complexité : **O(n log n)** (tous les cas).  
   - Divise et fusionne les sous-listes triées.  

### 5. **[Tri Rapide (Quick Sort)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Tri%20(Sort)/5-%20Rapide)**  

   - Complexité : **O(n log n)** (cas moyen), **O(n²)** (pire cas).  
   - Divise la liste en sous-listes autour d’un pivot.  


### 6. **[Tri Par Tas (Heap Sort)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Tri%20(Sort)/6-%20Tas)**  
   - Complexité : **O(n log n)** (tous les cas).  
   - Utilise une structure en tas pour trier.  


# **Algorithmes de Recherche :**

![SearchAlgorithms](https://github.com/user-attachments/assets/ee6619a3-ffc8-4515-9356-a13c5b89670b)

Cliquez sur les liens pour accéder aux algorithmes de recherche sur GitHub.  

### 1. **[Recherche Séquentielle (Linear Search)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Recherche%20(Search)/Dichotomique)**  
   - Complexité : **O(n)**.  
   - Parcourt chaque élément jusqu’à trouver l’élément recherché.  

### 2. **[Recherche Dichotomique (Binary Search)](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Recherche%20(Search)/S%C3%A9quentielle)**  
   - Complexité : **O(log n)** (liste triée).  
   - Divise la liste triée en deux moitiés pour localiser l’élément.


## **Naviguer par Catégorie**
- **[Dossier des Algorithmes de Tri](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Tri%20(Sort))**
- **[Dossier des Algorithmes de Recherche](https://github.com/mohamedtalhaouii/DSA/tree/main/Algorithmes/Recherche%20(Search))**


# **Complexité :**

![Big O](https://github.com/user-attachments/assets/57769ee1-5e07-4060-adbd-2a8a26838fab)

## Notation Big O
- **Définition :** Décrit la borne supérieure du temps d'exécution d'un algorithme. Elle donne le pire des cas de la manière dont le temps d'exécution augmente avec la taille de l'entrée.
- **Classes courantes :** 
  -  $`O(1)`$ : Temps constant. 
  -  $`O(\log n)`$ : Temps logarithmique. 
  -  $`O(n)`$ : Temps linéaire. 
  -  $`O(n \log n)`$ : Temps linéarithmique. 
  -  $`O(n^2)`$ : Temps quadratique. 
  -  $`O(2^n)`$ : Temps exponentiel. 
  -  $`O(n!)`$ : Temps factoriel. 


## Complexité temporelle :
- **Définition :** Mesure la quantité de temps qu'un algorithme prend pour s'exécuter en fonction de la longueur de l'entrée. 
- **Classes courantes :** 
    -  **P :** Problèmes résolubles en temps polynomial. 
    -  **NP :** Problèmes pour lesquels une solution donnée peut être vérifiée en temps polynomial. 
    -  **NP-difficile :** Problèmes aussi difficiles que les problèmes les plus difficiles de NP ; pas nécessairement dans NP. 
    -  **NP-complet :** Problèmes de NP qui sont NP-difficiles. 

## Complexité spatiale :
- **Définition :** Mesure la quantité de mémoire qu'un algorithme utilise en fonction de la longueur de l'entrée. 
- **Classes courantes :** 
    -  **PSPACE :** Problèmes résolubles en utilisant une quantité polynomiale d'espace. 
    -  **L :** Problèmes résolubles en espace logarithmique. 
    -  **NL :** Problèmes résolubles en espace logarithmique non déterministe. 

## Analyse de la Complexité :
- **Cas moyen** : Représente la complexité dans la plupart des situations. 
- **Pire cas** : La complexité la plus élevée, souvent analysée avec la notation $`Big-O`$. 
- **Meilleur cas** : La complexité minimale, mais rarement utilisée pour évaluer les performances globales. 

### Importance de la Complexité :
- **Optimisation** : La complexité aide à choisir l'algorithme le plus performant pour un problème donné, en fonction des ressources disponibles (temps et mémoire). 
- **Scalabilité** : Une bonne analyse de la complexité permet de savoir si un algorithme peut gérer de grandes tailles d'entrées de manière efficace. 

### Techniques pour Réduire la Complexité :
- **Diviser pour régner** : Diviser un problème en sous-problèmes plus petits, comme dans les algorithmes de tri (ex. tri rapide, tri fusion). 
- **Approximations** : Pour les problèmes NP-complets, utiliser des algorithmes d'approximation ou des heuristiques. 
- **Mémoïsation et programmation dynamique** : Stocker les résultats intermédiaires pour éviter les calculs redondants.

---

# **Structures de Données**
### **[🔝 Retour à l'index](#plan-du-contenu)**
*(soon as possible...)*
