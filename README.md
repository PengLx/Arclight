# Arclight

A Bukkit server implementation utilizing Mixin.

![Actions](https://img.shields.io/github/workflow/status/IzzelAliz/Arclight/Java%20CI%20with%20Gradle?style=flat-square)  ![GitHub](https://img.shields.io/github/license/IzzelAliz/Arclight?style=flat-square)

| Minecraft | Forge | Status | Build |
| :----: | :----: | :---: | :---: |
| 1.16.x | 34.1.7 | ACTIVE | [![1.16 Status](https://img.shields.io/appveyor/build/IzzelAliz/arclight-16?style=flat-square)](https://ci.appveyor.com/project/IzzelAliz/arclight-16) |
| 1.15.x | 31.2.45 | ACTIVE | [![1.15 Status](https://img.shields.io/appveyor/build/IzzelAliz/arclight-15?style=flat-square)](https://ci.appveyor.com/project/IzzelAliz/arclight-15) |
| 1.14.x | 28.2.0 | [LEGACY](https://github.com/IzzelAliz/Arclight/releases/tag/1.0.6) | [![1.14 Status](https://img.shields.io/appveyor/build/IzzelAliz/arclight?style=flat-square)](https://ci.appveyor.com/project/IzzelAliz/arclight) |

* Legacy version still accepts pull requests.

![](.github/arclightlogo.jpg)

## Installing

1. Download the jar from [release page](https://github.com/IzzelAliz/Arclight/releases) or build server. (see the table above)
2. Launch with command `java -jar arclight-forge-<mc>-<version>.jar nogui`. The `nogui` argument will disable the server control panel.

## Support

Discord server https://discord.gg/ZvTY5SC

QQ Group chat 3556966

## Contributing

This project uses Gradle 4.9 as build tool with [arclight-gradle-plugin](https://github.com/IzzelAliz/arclight-gradle-plugin).

To setup development workspace, clone this repository first, and type
```
./gradlew remapSpigotJar idea
```

This will generate proper spigot sources and srg mappings.

Finally, import the project. IntelliJ IDEA is the recommended IDE.

Due to a [MixinGradle bug](https://github.com/SpongePowered/MixinGradle/issues/9), you may build the project twice or the mixin shadows won't get reobfuscated.

## License

This project in licensed under [GPL v3](LICENSE).
