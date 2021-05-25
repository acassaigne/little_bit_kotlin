# little_bit_kotlin

Playing with kotlin

## first prog 

```kotlin
fun main() = println("Hello World!")
```

Pour compiler :

```bash
kotlinc Hello.kt -d Hello.jar
```

Pour exécuter

```bash
java -classpath Hello.jar HelloKt
```

Ou pour exécuter 

```bash
java -jar Hello.jar
```

Le mieux étant d'indiquer la librairie standard de kotlin :

```bash
java -classpath Hello.jar:$KOTLIN_PATH/lib/kotlin-stdlib.jar HelloKt
```

Autre façon d'exécuter (pas besoin de préciser $KOTLIN_PATH/lib/kotlin-stdlib.jar) :

```bash
kotlin -classpath Hello.jar HelloKt
```

Si mixte de java & kotlin il convient d'utiliser `java -classpath` par contre si c'est un projet uniquement kotlin alors utliser `kotlin`.