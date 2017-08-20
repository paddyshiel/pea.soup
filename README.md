# pea.soup

### Gradle Tasks:

#### Note
> In the following commands, when the version can be parameterised using a CI/CD build number.
> 
> `./gradlew clean build -Prelease.version=1.0.{bambooBuildNumber}`

#### Build
- build source
- run tests
- tag package

`./gradlew clean build -Prelease.version=1.0.0`

#### Release
- build and package application
- create a git tag

`./gradlew final -Prelease.version=1.0.0`

#### Publish
- standard publishing task to upload artifact repository

`./gradlew publish -Prelease.version=1.0.0`
