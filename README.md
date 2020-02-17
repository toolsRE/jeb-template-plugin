# JEB Back-End Plugin Template

Skeleton code to develop and test a JEB back-end plugin.

## Requirements

- A JEB license that supports back-end plugins (e.g. *JEB Pro* or *JEB Android*) version 3.1.1 or above.
- [IDEA IDE](https://www.jetbrains.com/idea/)
- [Ant](https://ant.apache.org/bindownload.cgi) 


## Getting Started

- Create a plugin folder and copy this repository: `git init MyPlugin && cd MyPlugin && git pull https://github.com/pnfsoftware/jeb-template-plugin`
- Open the project with IDEA (menu File, Open, ...)
- Start implementing your plugin (entry-point class: SamplePlugin) and your Tester's testPlugin() method

## Deploying

- menu Build, jebplugin, <default target>  (Ant is required)
- Copy the resulting Jar from the out/ folder to your JEB's coreplugins/ folder

## Tutorials

- [How to write an IR optimizer plugin for JEB's native decompilation pipeline](https://www.pnfsoftware.com/blog/jeb-native-pipeline-ir-optimizers-part-2/)

## Reference

- [API Documentation](https://www.pnfsoftware.com/jeb/apidoc/reference/packages.html)
