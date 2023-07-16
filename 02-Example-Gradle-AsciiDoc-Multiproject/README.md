# AsciiDoctor Gradle Multiproject

This repository is a template project for creating documentation in EPUB, HTML, and PDF formats using the AsciiDoctor syntax. The project is structured as an AsciiDoctor Gradle Multiproject and includes multiple subprojects serving as examples for books and articles.

## Contents

The template provides a prepared folder structure and configuration to facilitate the creation of documentation using AsciiDoctor and Gradle. The main contents of the project are:

- Templates for books and articles: The subprojects serve as templates that you can use to create your own documentation. You can start with the existing subprojects and customize them to meet your specific requirements.

- Sample content: The subprojects already contain example files and content to help you get started. You can edit these contents or add your own to shape your documentation.

## Usage

To use the template project, you can clone it and customize the contents to create your own documentation. The existing subprojects serve as a starting point and can be extended or modified as needed. You can also add new subprojects to create additional documentation.

## Building

To build the project, execute one of the following commands:

```bash
./gradlew build --parallel
./gradlew build --continuous
```

These commands will compile the project and generate the documentation in different formats.

## Deployment

There are several ways to deploy the project:

1. **Option I**: You can compile the project using the `./gradlew build` command and find the generated artifacts in the `build` directory. You can customize the `outputDir` parameter in the configuration to control the output location.

2. **Option II**: The `./gradlew aggregateArtifacts` command collects the artifacts from all subprojects and places them in a central location. You can customize the target folder for the aggregated artifacts in the Gradle configuration.

3. **Option III**: By using the commands `./gradlew distTar`, `./gradlew distZip`, and `./gradlew installDist`, you can package and deploy the project as a distribution. These commands create archives or install the project as a distribution.

## Communication

We appreciate your interest in this project! If you have any questions or suggestions for improvement, please feel free to use the issue tracker or contact us via email.

Let's create great documentation together!

*Note: This README.md serves as an example and can be customized according to the requirements and specifics of your own project.*

Sources:
- AsciiDoctor Documentation: [https://asciidoctor.org/docs/](https://asciidoctor.org/docs/)
- Gradle Documentation: [https://docs.gradle.org/](https://docs.gradle.org/)