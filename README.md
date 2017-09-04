# Scala Tutorial 

Tutoriel suivi sur TutorialPoints.

[Pour plus d'informations](https://www.tutorialspoint.com/scala/index.html).

## Example de base : Hello World

### Classe HelloWorld

```jsx
object HelloWorld{
    def main(args: Array[String]){
        println("Hello World !")
    }
}
``` 

### Compiler votre code
```jsx
scalac HelloWorld.class
```
### Exécuter une classe
```jsx
scala -classpath classes HelloWorld.class
ou 
scala HelloWorld
```
### Mode Alone
On a pas besoin d'écrire un script, on peut aussi utiliser la console de cette façon :
```jsx
scala 
```

## Conventions à respecter
* **Case Sensitivity:** Scala is case-sensitive, which means identifier Hello and hello would have different meaning in Scala.
* **Class Names:** the first letter should be in Upper Case. 

Example − class MyFirstScalaClass.
* **Method Names:** All method names should start with a Lower Case letter. 

Example − def myMethodName()
* **Program File Name:** Name of the program file should exactly match the object name. 

Example − Assume 'HelloWorld' is the object name. Then the file should be saved as 'HelloWorld.scala'.
* **def main(args: Array[String]):** Scala program processing starts from the main() method which is a mandatory part of every Scala Program.
* **/!\ '$' character** is a reserved keyword in Scala and should not be used in identifiers.


## Informations de bases sur le langage

### Importer un package
```jsx
import scala.xml._
import scala.collection.mutable.HashMap
import scala.collection.immutable.{TreeMap, TreeSet}
```

### Déclaration d'une variable
Variable muable (mutable) : qui peut changer
```jsx
var myVar : String = "Foo" 
```

Variable immuable (immutable) : une constante en qque sorte
```jsx
val myVal : String = “Foo”
```

### If Statement
```jsx
if(Boolean_expression 1){
   //Executes when the Boolean expression 1 is true
} else if(Boolean_expression 2){
   //Executes when the Boolean expression 2 is true
} else if(Boolean_expression 3){
   //Executes when the Boolean expression 3 is true
} else {
   //Executes when the none of the above condition is true.
}
```

### Do-While Loop
```jsx
do {
   statement(s);
} 
while( condition );
```

### For Loop
https://www.tutorialspoint.com/scala/scala_for_loop.htm
```jsx
scala 
```

### Déclaration d'une fonction
```jsx
def functionName ([list of parameters]) : [return type]
```


### Définition d'une fonction 
```jsx
def functionName ([list of parameters]) : [return type] = {
   function body
   return [expr]
}
```

### Déclaration d'un tableau : Array Type
Tableau uni-dimensionnel
```jsx
var z:Array[String] = new Array[String](3)
or
var z = new Array[String](3)
```

Tableau Multi-dimensionnel
```jsx
var myMatrix = ofDim[Int](3,3)
```


