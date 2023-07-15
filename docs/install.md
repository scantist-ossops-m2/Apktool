---
sidebar_position: 1
---

# Install Guide

:::info
A minimum of Java 8 is required for running Apktool.
:::

### Windows

1. Download Windows [wrapper script](https://raw.githubusercontent.com/iBotPeaches/Apktool/master/scripts/windows/apktool.bat) (Right click, Save Link As `apktool.bat`)
2. Download [latest](https://bitbucket.org/iBotPeaches/apktool/downloads) Apktool.
3. Rename downloaded jar to `apktool.jar`
4. Move both files (`apktool.jar` & `apktool.bat`) to your Windows directory (Usually `C://Windows`)
5. If you do not have access to `C://Windows`, you may place the two files anywhere then add that directory to your Environment Variables System PATH variable.
6. Try running `apktool` via command prompt

### Linux

1. Download Linux [wrapper script](https://raw.githubusercontent.com/iBotPeaches/Apktool/master/scripts/linux/apktool) (Right click, Save Link As `apktool`)
2. Download [latest](https://bitbucket.org/iBotPeaches/apktool/downloads) Apktool.
3. Rename downloaded jar to `apktool.jar`
4. Move both files (`apktool.jar` & `apktool`) to `/usr/local/bin` (root needed)
5. Make sure both files are executable (`chmod +x`)
6. Try running `apktool` via cli

### Mac

1. Download Mac [wrapper script](https://raw.githubusercontent.com/iBotPeaches/Apktool/master/scripts/osx/apktool) (Right click, Save Link As `apktool`)
2. Download [latest](https://bitbucket.org/iBotPeaches/apktool/downloads) Apktool.
3. Rename downloaded jar to `apktool.jar`
4. Move both files (`apktool.jar` & `apktool`) to `/usr/local/bin` (root needed)
5. Make sure both files are executable (`chmod +x`)
6. Try running `apktool` via cli

#### Brew

1. Install Homebrew as described [in this page](https://brew.sh/)
2. Execute command `brew install apktool` in terminal
3. Try running `apktool` via cli

:::tip
Wrapper scripts are not needed, but helpful, so you don't have to type `java -jar apktool.jar` repeatedly.
:::