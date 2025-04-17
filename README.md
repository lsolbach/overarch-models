# Overarch Models
This repository contains models for [Overarch](https://github.com/soulspace-org/overarch) that capture ideas for software development and related topics. This includes concepts, patterns, architecture blueprints, etc.

Currently it contains models about
* Software Architecture
* Cloud Computing
* Domain Driven Design
* DORA State of DevOps
* 12 Factor Apps

## Documentation generated from the models
* [List of Views](docs/views.md)

## Prerequisites
To generate diagrams and documentation for this model, you need to have Java 11+
and Graphviz installed.

## Generation
The project provides the JAR files for Overarch and PlantUML in the `tools` folder.

The `publish.sh` script in the root folder calls Overarch to render views and
template based artifacts, calls PlantUML and GraphViz to generate
images from the rendered views and publishes the generated artifacts to the
`docs` folder. It can form the basis for a CI/CD pipeline for automated artifact
creation.

The `overarch.sh` script in the root folder only calls Overarch to render views
and template based artifacts. Overarch is started in watch mode and will monitor
the model path for changes. When changed files are detected, the generation of
the artifacts will be triggered.

This script does not generate any images, but you
can use the preview features/plugins of your editor or IDE to see the images.

## Copyright and Licenses
The model files are © 2024 Ludger Solbach.
Licensed under [CC BY](https://creativecommons.org/licenses/by/4.0/).

### 12 Factor App
Copyright (c) 2012 Adam Wiggins.
Licensed under [MIT License](https://github.com/heroku/12factor/blob/main/LICENSE).

### Domain Driven Design
Domain Driven Design pattern descriptions by 
*Eric Evans, DOMAIN-DRIVEN DESIGN, Addison-Wesley, © Eric Evans, 2004.*
Licensed under [CC BY](https://creativecommons.org/licenses/by/4.0/).

### DORA
DORA is a program run by Google Cloud.
Licensed under [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/).
