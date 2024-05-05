## Location de voiture

**Ce projet une application console pour organiser une liste de voiture d'une agence de location**

### Installation
---

**Conditions**

Vous devez avoir un compilateur des fichiers .c pour pour pouvoir travailler avec ce projet dans votre ordinateur.

#### Compiler

Compiler le fichier.

```console
  ~$ gcc -o locationVoiture Location-de-voiture.c
```
#### Executer

Executer le fichier .exe.

```console
  ~$ locationVoiture.exe
```

### Usage
---

![image du menu](image/menu.png)

### Details
---

- **GESTIONAIRR** est application Console sert à stocker une liste de voiture dans un fichier Depot.txt.

- Le fichier Depot.txt est sous cette format :

![Format du fichier](image/text.png)

- L'application offre à l'utilisateur 6 fonction principale :
1. L'Affichage des données des produits de la liste.
2. L'ajout d'un produit à la liste.
3. La suppression d'un produit de la liste.
4. La modification d'une donné d'un produit de la liste.
5. La recherche d'un produit de la liste.
6. Le triage de la liste.


- Elle extrait les données du fichier en utilisant la fonction "extraire" qui ouvre le fichier et puis remplir la liste chaînée "voitures".

- Après que l'utilisateur sort du programme les modifications appliquées sur "voitures" vont être insérer au fichier "Depot.txt".

#### Ajout 
---

En utilisant la commande "1".

#### Modification 
---

En utilisant la commande "2".

#### Suppression 
---

En utilisant la commande "3".

### Affichage
---

En utilisant la commande "4".

#### Recherche 
---

il existe 2 choix de recherche :
- **La recherche avec la marque**: En utilisant la commande "5".
- **La recherche avec la disponibilité**: En utilisant la commande "6".

#### Triage
---

il existe 2 choix triage :
- **Triage par marque**: En utilisant la commande "7".
- **Triage par prix de location**: En utilisant la commande "8".
