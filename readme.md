# CycloneDX Gradle plugin update has no links

## Current behavior

Renovate PRs that update the `org.cyclonedx.bom` Gradle plugin have no link to the source repository or the release notes.
The plugin marker POM (`org.cyclonedx.bom:org.cyclonedx.bom.gradle.plugin`) has no `scm` or `url`.

## Expected behavior

Renovate PRs link to the [source repository](https://github.com/CycloneDX/cyclonedx-gradle-plugin) and the [releases](https://github.com/CycloneDX/cyclonedx-gradle-plugin/releases).
