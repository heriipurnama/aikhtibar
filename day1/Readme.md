# kotlin -version

# Compiling Kotlin program

kotlinc intermezzo.kt 

kotlin IntermezzoKt.class <br>
    Hello, World!

# Packaging Kotlin program
kotlinc intermezzo.kt -include-runtime -d intermezzo.jar

java -jar intermezzo.jar <br>
    Hello, World!