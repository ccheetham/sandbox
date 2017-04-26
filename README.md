## Publishing Requirements
To configure artifactory credentials, do one of:
* edit ~/.pivotal/credentials.properties to include
  * `tcsArtifactoryUser` - The username for Artifactory instance
  * `tcsArtifactoryPassword` - The password for Artifactory user
* edit ~/.gradle/gradle.properties to include
  * `artifactoryUser` - The username for Artifactory instance
  * `artifactoryPassword` - The password for Artifactory user
* set environment variables (used by Jenkins)
  * `ARTIFACTORY_USER` - The username for Artifactory instance
  * `ARTIFACTORY_KEY` - The password for the Artifactory user
