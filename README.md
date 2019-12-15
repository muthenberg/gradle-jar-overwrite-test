# gradle-jar-overwrite-test
This is a simple non working example for publishing a proguard JAR using a Gradle build file. It is used to get support via stackoverflow.

To see the problem described by this project just run `./gradlew publish`.

The goal of this project is to use the Gradle publish plugin to publish a JAR file that was obfuscated by proguard as a Maven artifact.
For this to happen the unobfuscated JAR needs to be replaced, which should be possible by providing a custom configuration.
Unfortunately the Gradle documentation is not very clear on how to achieve this: (https://docs.gradle.org/current/userguide/publishing_customization.html)[https://docs.gradle.org/current/userguide/publishing_customization.html]
