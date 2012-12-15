archetype-android-simple
========================

Maven archetype to generate android project ready for release and site generation.
In addition all files needed by Eclipse are generated.

1. Run:

    `mvn clean install`

2. Then you are able to run:

      mvn archetype:generate -D archetypeCatalog=local \
			     -D archetypeGroupId=com.fleurey.android \
			     -D archetypeArtifactId=archetype-android-simple