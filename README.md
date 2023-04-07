# Codelijst-archetype
Maven archetype voor het opzetten van een nieuw codelijst project structuur.
# Gebruik
Voer het volgende maven commando uit om een folder structuur van een codelijst project te genereren. Pas eerst de waarde van -DartifactId aan.
```
mvn archetype:generate -B -DarchetypeGroupId=be.vlaanderen.omgeving.maven.archetype -DarchetypeArtifactId=codelijst-archetype -DarchetypeVersion=0.3.0 -DartifactId=codelijst-test
```
Verplichte conventie: -DartifactId=codelijst-{lokale_identificator_codelijst}.

Voorbeeld: -DartifactId=codelijst-test waarbij test de lokale identificator van de codelijst is.