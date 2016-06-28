# docker-swift

[![Docker Stars](https://img.shields.io/docker/stars/sbstjn/swift.svg?maxAge=600)](https://hub.docker.com/r/sbstjn/swift/) [![Docker Pulls](https://img.shields.io/docker/pulls/sbstjn/swift.svg?maxAge=600)](https://hub.docker.com/r/sbstjn/swift/)

Create a `Dockerfile` with `FROM sbstjn/swift:3.0-preview-1` and everything is set up for you. Make sure to follow the basic conventions of having a `Tests/` folder and a `Package.swift` file.

The Dockerfile will copy all files from `Sources/` and `Tests/` to the container and execute `swift build` and `swift test` afterwards.

Use [sbstjn/Boilerplate.swift](https://github.com/sbstjn/Boilerplate.swift) to get started!
