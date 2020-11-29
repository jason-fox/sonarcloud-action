# SonarCloud GitHub action

This action installs Java 11 and runs Maven over the root of the project

## Inputs

### `path-to-pom`

The name of the [Maven POM](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html) to upload the Sonarcloud results. Defaults to `./pom.xml` if not supplied.

## Example usage

```yaml
uses: jason-fox/sonarcloud-action@master
```
