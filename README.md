# jakartaee9-essentials-archetype

Arquetipo en Maven para crear proyectos Jakarta EE 9.

Para instalarlo localmente ejecute:

```
./mvnw install
```

## Creación de un nuevo proyecto Jakarta EE 9

Para crear proyectos utilizando este arquetipo, ejecute en una ubicación en blanco:

```
mvn -DarchetypeGroupId=com.apuntesdejava \
    -DarchetypeArtifactId=jakartaee9-essentials \
    org.apache.maven.plugins:maven-archetype-plugin:generate
```

El maven le pedirá los valores del proyecto que está creando.

Además, puede utilizar el IDE de su preferencia.