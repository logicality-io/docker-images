# Docker Images

A collection of docker images used to build services and applications or as base images services.

All images are rebuilt on a weekly schedule to include the latest version of the embedded tools, SDKS etc.

| Image | Tools | Description |
|---|---|---|
| dotnet | .NET 6.0 SDK latest, git, docker-cli, zip | Used to build .NET libraries and applications.|
| dotnet-node | Based on `dotnet:latest`, nodejs, npm | Used to build .NET based projects with .NET backends and NodeJS based frontends. |
