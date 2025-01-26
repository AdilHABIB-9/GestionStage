# Gestion des Stagiaires et Stages

## Description
Ce projet est une application Java conçue pour gérer les stagiaires et les stages. Il permet d'ajouter, de supprimer et d'afficher les stagiaires et les stages associés. L'application est interactive, utilisant un menu pour naviguer entre les différentes fonctionnalités.

## Fonctionnalités
- Ajouter un stagiaire
- Afficher la liste des stagiaires
- Supprimer un stagiaire
- Ajouter un stage
- Afficher la liste des stages
- Supprimer un stage

## Structure du Code
Le projet est composé des classes suivantes :

1. **Personne**
   - Représente une personne avec un nom et un prénom.
   - Méthode `afficher()` pour afficher les informations.

2. **Stagiaire**
   - Hérite de la classe `Personne`.
   - Ajoute un attribut `niveauEtude`.
   - Méthode redéfinie `afficher()` pour inclure le niveau d'étude.

3. **Stage**
   - Représente un stage avec un titre et une durée.
   - Contient une liste de stagiaires.
   - Méthode `ajouterStagiare()` pour ajouter un stagiaire au stage.
   - Méthode `afficher()` pour afficher les informations du stage et des stagiaires associés.

4. **GestionStagiaires**
   - Gère les opérations sur les stagiaires.
   - Méthodes : `ajouter()`, `supprimer()`, `afficher()`.

5. **GestionStages**
   - Gère les opérations sur les stages.
   - Méthodes : `ajouter()`, `supprimer()`, `afficher()`.

6. **Gestion**
   - Interface définissant les méthodes communes `ajouter()`, `supprimer()`, `afficher()`.

## Utilisation
Pour utiliser l'application, compilez et exécutez la classe `Main`. Un menu interactif permettra de choisir les différentes opérations à effectuer.

```java
public class Main {
    public static void main(String[] args) {
        // Votre code ici
    }
}
