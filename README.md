mvn archetype:generate
    - Dgroup = com.mycompany.app
    - DartifactId = my-app
    - DarchetypeArtifactId = maven-archetype-simple
    - DarchetypeVersion = 1.4
    - DinteractiveMode = false

Rega de nomenclatura:
Llamar al proyecto por nuestro dominio, seguido del nombre del proyecto:

Arquetipos:
hay una guia en maven.apache.org
se suele coger maven-archetype-simple, ó maven-archetype-simple

mvn archetype:generate
    - Dgroup = org.edumarrom.miapp
    - DartifactId = miapp
    - DarchetypeArtifactId = maven-archetype-quickstart
    - DarchetypeVersion = 1.4
    - DinteractiveMode = false
