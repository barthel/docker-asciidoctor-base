# Asciidoctor Base/Original &mdash; multi platform Edition

## ⚠️ NO LONGER MAINTAINED

The original [Asciidoctor Docker image](https://github.com/asciidoctor/docker-asciidoctor) is delivered from version [*1.63.0*](https://github.com/asciidoctor/docker-asciidoctor/releases/tag/1.63.0) as a multi platform container with `amd64` and `arm64`.

For this reason, this repository/container image is no longer required and will no longer be maintained.

----

The goal of this project is to build a multi platform (amd64, arm64) Docker image based on the original [Asciidoctor Docker image](https://github.com/asciidoctor/docker-asciidoctor) using Alpine Linux.

## ⚠️ Note

Unfortunately, it is not possible to provide **`armv7`** version greater than [1.46](https://github.com/barthel/docker-asciidoctor-base/releases/tag/1.46.0) anymore because updated Java-based tools no longer use Java 8 and there is no Java runtime environment greater than version 8 on Alpine Linux **`armv7`**.

Docker Hub: https://hub.docker.com/r/uwebarthel/asciidoctor-base
