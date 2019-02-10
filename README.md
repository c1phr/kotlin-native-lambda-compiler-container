# Kotlin/Native Lambda Compiler Container
Since Kotlin/Native doesn't have a virtual machine, it must be built for the platform that it's intended to be run on. 
For Kotlin/Native Lambda users who are not using a Linux machine running a flavor of Amazon Linux, Docker can enable building for a Linux target on other platforms.
This container [c1phr/kotlin-native-lambda-runtime-compiler](https://hub.docker.com/r/c1phr/kotlin-native-lambda-runtime-compiler) attempts to mirror the [Lambda Execution Environment](https://docs.aws.amazon.com/lambda/latest/dg/current-supported-versions.html) (plus the Kotlin/Native compiler) to provide 
an environment close to that in which your Lambda function will run.

This is intended to be used with the Kotlin/Native Lambda Runtime found [here](https://github.com/c1phr/lambda-runtime-kotlin-native).
