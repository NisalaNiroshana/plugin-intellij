# Ballerina plugin for IntelliJ IDEA

## Building from the source

1. Clone the repository using the following command.
```
git clone --recursive https://github.com/ballerinalang/plugin-intellij.git
```
2. Install latest version of [Gradle](https://gradle.org/) if you don't have it installed already.
3. Navigate into the cloned repository and run `gradle buildPlugin`.
4. In the **build/distributions** directory, **Ballerina-Intellij-Plugin.zip** will be created.

## Installing the plugin to IDEA
1. Go to **File -> Settings** and select **Plugins**.
2. Click **Install plugin from disc** button and select the deployed **plugin zip** file. Please make sure to install the Zip file, not the extracted Jar files. This zip contains an additional library as well. Without this library, the plugin will not work properly.
3. Restart IDEA.


## Getting started

Please refer the [Getting Started](getting-started) section.

## How to contribute
Pull requests are highly encouraged and we recommend you to create a GitHub issue to discuss the issue or feature that you are contributing to.

## License
Ballerina IDEA plugin source is available under the Apache 2.0 License.

## Copyright
Copyright (c) 2017, WSO2 Inc. (http://www.wso2.org) All Rights Reserved.
