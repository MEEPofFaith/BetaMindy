![Logo](assets/icon-small.png)

[![Discord](https://img.shields.io/discord/704355237246402721.svg)](https://discord.gg/RCCVQFW) [![Language](https://img.shields.io/badge/made%20with-Scratch%202.0-orange)]() [![Stars](https://img.shields.io/github/stars/sk7725/BetaMindy?label=Please%20Star%20Me%21&style=social)]()


# BetaMindy
A java mod for testing and doing chaotic fun.

## Enjoying
1. Go to [Actions](https://github.com/sk7725/BetaMindy/actions), and click on the latest workflow, starting with the name "Stable".   
2. Select the "normal" Artifact (with the box icon), it will download the zip.   
3. Unzip and paste the `.jar` into your mod folder.   
4. Enjoy!   

## Compiling
JDK 8.

### Windows
Plain Jar: `gradlew build`\
Dexify Plain Jar: `gradlew dexify`\
Build Plain & Dexify Jar: `gradlew buildDex`

### *nix
Plain Jar: `./gradlew build`\
Dexify Plain Jar: `./gradlew dexify`\
Build Plain & Dexify Jar: `./gradlew buildDex`

Plain Jar is for JVMs (desktop).\
Dexed Jar is for ARTs (Android). This requires `dx` on your path (Android build-tools).\
These two are separate in order to decrease size of mod download.
