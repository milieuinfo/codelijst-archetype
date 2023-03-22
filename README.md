# codelijst-archetype
Maven archetype voor het opzetten van een nieuw codelijst project

## Gebruik

- vanuit folder waar je codelijst project lokaal wilt hebben:

### voorbeeld => maak een nieuw project met de naam 'test'
```
cd ~/git
mvn archetype:generate -B -DarchetypeGroupId=be.vlaanderen.omgeving.maven.archetype -DarchetypeArtifactId=codelijst-archetype -DarchetypeVersion=0.1.0 -DartifactId=codelijst-test
```
