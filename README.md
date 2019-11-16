# Gradle Web Console

The one and only Gradle web console.
It allows the user to execute a single build script using the Groovy DSL from within your browser, no installation required.

This project is a proof-of-concept (POC).
The service quality may degrade or stop working without notice.
There may also be bugs.
If you feel brave enough, open GitHub issues for any bugs, features or improvements you would love to see.
Once the source code will be public, you will be able to contribute.
Feel free to vote on [this issue if you want to have access to the source code faster](https://github.com/lacasseio/gradlewebconsole/issues/2).

## Features

- Live edit a Groovy DSL build script directly in the browser
- Execute any Gradle command directly in the browser on the authored build script
- Share a quick link to your build script in this console: https://gradleconsole.lacasse.io/?content=dGFza3MucmVnaXN0ZXIoInNheUhlbGxvIikgewogICAgZG9MYXN0IHsKICAgICAgICBwcmludGxuKCJIZWxsbyBldmVyeW9uZSB3aXRoIHRoaXMgbGluayEiKTsKICAgIH0KfQoK
    - NOTE: The link is quite long because it's only a dumb base64 of the script
- Every Gradle commands gets a [build scan](https://scans.gradle.com/)!

