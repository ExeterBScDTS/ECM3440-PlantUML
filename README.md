# ECM3440-PlantUML

## PlantUML

<https://plantuml.com/>

### VS Code extension

<https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml>

### Introduction

<https://www.codeproject.com/Articles/1278703/UML-Made-Easy-with-PlantUML-VS-Code>

### Installing the server

The VS Code extension makes use of the PlantUML server at <http://www.plantuml.com/plantuml> so installing your own server is not normally required.  If you do choose to install the server the Docker is recommended.

```sh
docker run -d -p 8080:8080 plantuml/plantuml-server:jetty
```

See <https://github.com/plantuml/plantuml-server> for more details.
