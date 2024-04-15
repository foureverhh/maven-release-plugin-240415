# maven-release-plugin-240415

## https://www.youtube.com/watch?v=x7Su57miuQI

## mvn -B release:prepare 
- rise version tag with 1 for example 1.0.0-SNAPSHOT -> 1.0.1-SNAPSHOT
- git commit and push the rised SNAPSHOT to scm
- it generates pom.xml.releaseBackup and release.properties, besides pom.xml


## mvn -B release:perform
- remove -SNAPSHOT and create artifactory to git repo

