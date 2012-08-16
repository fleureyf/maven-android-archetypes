archetype-android-full
========================

Maven archetype to generate android project and android test project using Robotium.
In addition all files needed by Eclispe are generated.

Just run:

`mvn clean install`

then you are able to run:

`mvn archetype:generate -D archetypeCatalog=local`

Or with property values:

    mvn archetype:generate  -D archetypeCatalog=local\
                            -D groupId=org.yourcompany.android\
                            -D artifactId=sample\
                            -D androidSdkPath=/path/to/sdk\
                            -D gitHost=<your project git hosting>\
                            -D gitRepoOwner=<the project owner>\
                            -D gitRepoName=<the project repository>