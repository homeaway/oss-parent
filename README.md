oss-parent
==========

Parent pom for oss maven projects at homeaway.

## Deploying

Make sure that you do the following:
* Sign up [here](https://issues.sonatype.org/browse/OSSRH).
* Create a ticket, requesting access to the com.homeaway groupId.
* Add your username and password to your `~/.m2/settings.xml`, with
  the following `server` tags
  ```xml
      <server>
      <id>sonatype-nexus-snapshots</id>
      <username>username</username>
      <password>password</password>
    </server>
    <server>
      <id>sonatype-nexus-staging</id>
      <username>username</username>
      <password>password</password>
    </server>
  ```
