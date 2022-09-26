# Syllabus Angular Formations

# First part

```
   required : 
   - git and github
```
## 1 - Historique et Fonctionnalités apportés par ES2015
```
  - Translipteur
  - 
```
## 1 - setup environnement
```
  - https://angular.io/guide/setup-local
```

## 2 - Typescript
```
  - syntax de declaration

  var <variable>:<type> = valeur
  - inferrence de type

  var x = "test"
  - Duck Typing

  var complexType = {"x": "v1", "y":"v2"}
  - Type  Any

  var
  - Rest parameter

  - spread operator
  
```

## 4 - Angular cli
```
    - 
    -
    -
    -

 https://angular.io/guide/what-is-angular
```

## 5 - First project
```
  - generate a project :
  ng new [project_name]
  - Architecture Angular
  - explain the code generated
```

## 6 - Elements de base

```
  - Composant
 

  - Interpolation
  {{}}
  - Directives
      - Directives structurelles NgIf,NgFor,NgSwitch
      - Autres Directives NgClass, NgStyle
      - Propre directive  : 
      Les sélecteurs peuvent être de différents types :
      • un élément, comme c’est généralement le cas pour les composants : footer.
      • une classe, mais c’est plutôt rare : .alert.
      • un attribut, ce qui est le plus fréquent pour une directive : [color].
      • un attribut avec une valeur spécifique : [color=red].
      • une combinaison de ceux précédents : footer[color=red] désignera un élément footer avec un
      attribut color à la valeur red. [color],footer.alert désignera n’importe quel élément avec un
      attribut color, ou (,) un élément footer portant la classe CSS alert. footer:not(.alert) désignera
      un élément footer qui ne porte pas (:not()) la classe CSS alert.

      
  - Pipes
     https://angular.io/guide/pipes
     Le mot « pipe » vient de l’anglais « pipeline », terme également utilisé en français. En informatique, un pipe désigne un flux de données exécuté entre deux processus étroitement liés, ou n’ayant au contraire aucune origine commune. Cela signifie que le résultat de sortie d’un programme peut servir d’entrée à un autre. Cela permet, entre autres, de diviser des problèmes complexes en sous-problèmes plus petits, et de profiter ainsi d’une meilleure vue d’ensemble.
     source : https://www.ionos.fr/digitalguide/serveur/configuration/pipes-linux/
  - Communication entre composant
  ```
    Concept qui permet à Angular d'echanger des informations entre un composant parent et un composant.
    Faire un exemple
  ```
  Generate un composant : 
  - Definir un composant
  - ng generate component 
  - Explication du code généré (pattern decorateur)
  - Interpolation
  - Imbrication de composant
     * Declarer notre composant dans le module
     * Binding de propriété
```