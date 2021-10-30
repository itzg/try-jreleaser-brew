This project attempts to use the [JReleaser Homebrew packager](https://jreleaser.org/guide/latest/configuration/packagers/homebrew.html) with [the Gradle plugin](https://jreleaser.org/guide/latest/tools/jreleaser-gradle.html).

## Output

```
> gradlew build

Welcome to Gradle 7.1!

Here are the highlights of this release:
 - Faster incremental Java compilation
 - Easier source set configuration in the Kotlin DSL

For more details see https://docs.gradle.org/7.1/release-notes.html

Starting a Gradle Daemon, 2 incompatible and 3 stopped Daemons could not be reused, use --status for details

FAILURE: Build failed with an exception.

* Where:
Build file 'E:\Users\Geoff\Downloads\try-jreleaser-brew\build.gradle' line: 25

* What went wrong:
A problem occurred evaluating root project 'try-jreleaser-brew'.
> Cannot set the value of read-only property 'owner' for root project 'try-jreleaser-brew' of type org.gradle.api.Project.
```