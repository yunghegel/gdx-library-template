Uses reposilite for deployment.
In gradle.properties, define credentials for "snapshot" and "release" repositories like this:
```properties
snapshotUsername=...
snapshotPassword=...

releaseUsername=...
releasePassword=...
```

In config.gradle, define your repository base url, artifact id, group, and version.

Deploys as a snapshot by default, set RELEASE to true to deploy as a release.

