# 11.1 Warming up

Let's assume we have a **Python** application being worked on by a team of around 6 people.

For Python, the most popular linter is probably Pylint by Microsoft. Other linting libraries are, for example, flake8 and mypy, both also published by Microsoft, and community-published Ruff. For testing, Python is equipped with the built-in unittest framework. As Python is an interpreted language, there is no need for compiling the application, however, the build step might consist of, for example, copying everything to a build directory.

There are a lot of alternatives for setting up the CI. Besides Jenkins and GitHub Actions, some popular solutions are GitLab CI/CD, CircleCI, and Travis CI. They are all cloud-based, but there are also different self-hosted alternatives, like Buildkite.

Whether to choose self-hosted or a cloud-based environment depends on a few key factors. Generally, unless the project is really complex and the scale is large, a cloud-based CI is probably a better solution. A cloud-based CI is easier to set up and maintain. For more complex and special needs the self-hosted CI might be better. This can be the case for larger scale projects. For a team of 6 people, the cloud-based environment is probably suitable, assuming the features of the cloud-based solutions are sufficient.
