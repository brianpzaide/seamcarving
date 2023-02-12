# Seam Carving

This is a project from Jetbrains Academy.

### Building an app into a JAR file

Run `docker container run -v $(pwd):/app --rm zenika/kotlin kotlinc /app -include-runtime -d /app/sc.jar`

### Running the JAR file

Run `docker container run -v $(pwd):/app --rm zenika/kotlin java -jar /app/sc.jar -in trees.png -out trees-reduced.png -width 100 -height 30`
