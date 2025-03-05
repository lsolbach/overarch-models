# Overarch Models
This repository contains models for  [Overarch](https://github.com/soulspace-org/overarch) that capture ideas for software development and related topics. This includes concepts, patterns, architecture blueprints, etc.

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

## Copyright
The model files are © 2024 Ludger Solbach.

For the information in the models, additional copyrights may apply, which are
documented in the READMEs in the respective model folders.

## License

