# Test for Overwriting Gradle Publication JAR with Obfuscated ProGuard Jar during Publication
This is a simple example for publishing an obfuscated Proguard JAR using Gradle and its 'publish' plugin. It is used to get support via stackoverflow.

The most important requirement was, that only the obfuscated Proguard JAR must be published as a substitute for the not obfuscated one. So simply adding a classifier does not solve the issue.

I did ask the relevant question (https://stackoverflow.com/questions/59343095/how-to-publish-proguard-jar-as-maven-artifact-using-gradle-publish-plugin)[here].
The final solution is based on (https://stackoverflow.com/questions/52875698/how-to-proguard-with-spring-boot-gradle-plugin)[this] thread.

To see the solution in action just run `./gradlew publish`.
