archetype-android-full
========================

Maven archetype to generate android project and android test project using Robotium.
In addition all files needed by Eclispe are generated.

1. Run:

    `mvn clean install`

2. Then you are able to run:

    `mvn archetype:generate -D archetypeCatalog=local`

    Or with property values:

        mvn archetype:generate -D archetypeCatalog=local -D groupId=org.yourcompany.android -D artifactId=sample -D androidSdkPath=path-to-sdk -D gitHost=<project-git-hosting> -D gitRepoOwner=<project-owner> -D gitRepoName=<project-repository>