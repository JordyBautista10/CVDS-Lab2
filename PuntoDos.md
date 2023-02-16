mvn archetype:generate -DgroupId=edu.eci.cvds
                       -DartifactId=Patterns 
                       -DarchetypeArtifactId=maven-archetype-quickstart
                       -DinteractiveMode=false
                       -Dpackage=edu.eci.cvds.patterns
                       
mvn archetype:generate -DgroupId=edu.eci.cvds -DartifactId=Patterns -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -Dpackage=edu.eci.cvds.patterns

cd Patters
mvn tree

![image](https://user-images.githubusercontent.com/123812969/219262922-721c396e-d146-4622-89c3-e28e69f25540.png)

