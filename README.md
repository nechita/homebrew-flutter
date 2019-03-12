# Flutter

Forked the original tap in order to be able to upgrade flutter to newer version.

Currently installs flutter latest stable version in flutter/flutter github (https://github.com/flutter/flutter)

## Installation:

```shell
$ brew tap nechita/homebrew-flutter
$ brew install flutter
```

## Upgrade

```shell
$ brew upgrade flutter
```
or
```shell
$ flutter upgrade
```

## Uninstallation:

```shell
$ brew uninstall flutter
```

## Post-Installation:

flutter path will be

  `/usr/local/opt/flutter`

dart-sdk path will be

  `/usr/local/opt/flutter/bin/cache/dart-sdk`

If you're located in China, please follow：

  https://github.com/flutter/flutter/wiki/Using-Flutter-in-China

After installed,run the following command to see if there are any platform dependencies you need to complete the setup:


  ```shell
  $ flutter doctor
  ```
  
