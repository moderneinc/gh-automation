# Moderne Inc. GitHub Automation

Public reusable GitHub Actions workflows.

| Workflow | Purpose |
|----|----|
| [ci-gradle](.github/workflows/ci-gradle.yml) | Standardized way to checkout and build / test a Gradle application |
| [publish-maven-artifact](.github/workflows/publish-maven-artifact.yml) | Tag a release of a Gradle library, publish it, and cut a GitHub release |
| [publish-containerized-gradle-app](.github/workflows/publish-containerized-gradle-app.yml) | Build and publish a release Docker image of a Gradle application to ECR |
| [publish-containerized-snapshot](.github/workflows/publish-containerized-snapshot.yml) | Build and publish a snapshot Docker image of a Gradle application to ECR |
| [repository-backup](.github/workflows/repository-backup.yml) | Back-up repository to AWS S3 bucket |

Public OpenRewrite repositories use the equivalents in
[openrewrite/gh-automation](https://github.com/openrewrite/gh-automation) instead.
