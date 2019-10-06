# darrenjw's solution attempt

Here is a solution to the A-star / atomic space helicopters problem in Scala.

To compile and run, you just need a vaguely recent [JDK](http://www.oracle.com/technetwork/java/javase/downloads) (eg. `openjdk-8-jdk` is fine on Linux) and [sbt](https://www.scala-sbt.org/).

Do:
```bash
sbt run
```
to build and run with the default field (`field1.json`). To run with another field, just pass in its name as an argument. eg.
```bash
sbt "run maze.json"
```

There is a reasonably generic a-star algorithm implementation in [a-star.scala](src/main/scala/a-star.scala). It is a pure functional translation of the pseudo-code given on the [A-star algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm) wikipedia page, making extensive use of Scala's standard library immutable collections.

The application to the atomic space helicopters problem is given in [a-star-example.scala](src/main/scala/a-star-example.scala). This is still essentially functional, though it could do with a refactor to clean up and make more modular.



