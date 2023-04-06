# Codelijst-archetype
Maven archetype voor het opzetten van een nieuw codelijst project structuur.
# Gebruik
Voer het volgende maven commando uit om een folder structuur van een codelijst project te genereren:
```
mvn archetype:generate -B -DarchetypeGroupId=be.vlaanderen.omgeving.maven.archetype -DarchetypeArtifactId=codelijst-archetype -DarchetypeVersion=0.2.0 -DartifactId=codelijst-test
```
Pas de waarde van -DartifactId aan volgens de verplichte conventie: -DartifactId=codelijst-{lokale_identificator_codelijst}.

Voorbeeld: -DartifactId=codelijst-test waarbij test de lokale identificator van de codelijst is.