#   Scala Tutorial for yourself
## Basic Syntax and introduction
Start your Scala in your command line tool(For windows) or terminal(Mac/Linux)

```scala
scala> println("Hello World!")
```
The result will be:
```Hello World!```
Also there is an another way to prompt Scala code.
First open your editor or IDE such as Intellij Idea and creat a **HelloWorld.scala** file and types in

```scala
Object HelloWorld{
    def main(args:Array[String]}{
        println("Hello,World!")//scala do not care if there is a ; line
    }
}
```
Open your terminal and prompt:

```Bash
>scalac HelloWorld.scala
>scala HelloWorld
>Hello,World!
```
In this tutorial, I suppose that you have already known how to compile java programs and run java classes. 
As you can see from the **HelloWorld.scala** file:
The **def main(args:Array[String])** is the way that scala create it functions which is very similar to python language.(I have used python for a rather long time. So the first time I saw the definition, I was amazed by this declaration, and it is also similar to Java.)
### How to name your Scala variables
Every language should have their variables and the rule to name those identifiers. Scala provide a standard identification rule as Java which means you can use either a letter or underscore to start your identifiers.
Several examples are provided:
```year, _length, mineCraft```
### Operator Identifiers
An operator identifier consists of one or more operator characters.Like
```+ ++ ::: <?> :>```
### Some scala keywords
| Keyword | keyword | Keyword |
| --- | --- | --- |
| Abetract | Case | catch |
| False | Do | class |
Still there are many keywords in Scala.



