# CI in Java

## Linting

The most popular linting tool for Java seems to be Checkstyle. Other alternatives include PMD, SpotBugs and SonarQube.

## Testing

Java projects can be tested with libraries such as JUnit and Mockito (unit testing), TestNG (unit and integration testing), and Selenium (e2e testing).

## Building

Some of the more popular tools for building Java applications are Apache Ant, Apache Maven and Gradle.

## CI pipelines

Other than Jenkins and Github Actions, the most commonly used alternatives for CI tooling are Azure DevOps (very similar to GH Actions) and AWS CodePipeline.

## Self-hosted or cloud-based?

For this setup, I would choose a cloud-based environment. This is mainly motivated by the simple fact that it is much simpler to set up, and as I am new to CI pipelines, it feels natural to choose the option that is the easiest to get into as someone who is presently just a solo developer. I would not consider switching to a self-hosted setup until I have an actual need for some of the special features, such as utilising a graphics card during the testing/building process. Specifically, I would use GitHub Actions, as I would almost certainly be hosting the code itself on GitHub.
