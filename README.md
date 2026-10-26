# AstraCraft

**[CURRENTLY IN DEVELOPMENT]**

An advanced minecraft space exploration mod powered by a fully customizable procedural planetary and solar system generation engine

## Development client

AstraCraft includes the neighboring `../AstraLib` Gradle build as a composite
dependency. Run the client from this project with:

```powershell
.\gradlew.bat runClient
```

Gradle builds AstraLib's mod JAR when needed and loads it as a separate runtime
mod in the AstraCraft development client.

Build both mods from AstraCraft with:

```powershell
.\gradlew.bat build
```

The standalone mod JARs remain in `AstraCraft/build/libs` and
`AstraLib/build/libs`. The `build` task also assembles the latest AstraCraft and
AstraLib JARs together, without nesting either one, in `AstraCraft/build/modpack`.
Install both JARs from that folder in the modpack.
