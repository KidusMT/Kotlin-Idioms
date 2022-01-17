<p align="center">
     <img width="430" height="200" src="https://user-images.githubusercontent.com/18373774/149808967-1a63ab8b-316c-4645-a781-9c1a875d38cc.png" alt="kotlin logo"/>
<p>

     
## [Filters](https://stackoverflow.com/a/50788929/6021740)
```kotlin
val names = arrayOf("one", "two", "three", "four" )
val anotherNames = arrayOf( "one", "five", "ten" )
println(names.filter { it in anotherNames })
println(names.filter { it in anotherNames }.isNotEmpty())
```
`>> [one]`
     
`>> true`
