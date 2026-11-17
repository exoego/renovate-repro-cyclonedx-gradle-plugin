# CycloneDX Gradle plugin update has no links

## Current behavior

Renovate PRs that update the `org.cyclonedx.bom` Gradle plugin have no link to the source repository or the release notes.
The plugin marker POM (`org.cyclonedx.bom:org.cyclonedx.bom.gradle.plugin`) has no `scm` or `url`.

Example: #1 (created by Mend Renovate)

## Expected behavior

Renovate PRs link to the [source repository](https://github.com/CycloneDX/cyclonedx-gradle-plugin) and the [releases](https://github.com/CycloneDX/cyclonedx-gradle-plugin/releases).

Example: #3 (created by Renovate CLI with the fix)

## Link to the Renovate PR

https://github.com/renovatebot/renovate/pull/48124
