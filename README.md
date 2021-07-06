# Merged with [flutter-riverpod-snippets](https://github.com/RobertBrunhage/flutter-riverpod-snippets)

![status: archive](https://img.shields.io/badge/status-archive-red) &nbsp;
![status: discontinued](https://img.shields.io/badge/status-discontinued-red)

# **!Important**

This repository has been merged with [RobertBrunhage/flutter-riverpod-snippets](https://github.com/RobertBrunhage/flutter-riverpod-snippets) this repository will be archived for reference.

Please install [flutter-riverpod-snippets](https://marketplace.visualstudio.com/items?itemName=robert-brunhage.flutter-riverpod-snippets) extension available on VS Code.

# Riverpod and Freezed Snippets

With the help of Riverpod and Freezed snippets users can easily work with Riverpod and be more productive. This extension contains different riverpod and freezed snippets.

## Features

- Speeds up state management with Riverpod
- Easy to use

## Requirements

Vscode: `1.56.0`

## Snippets

| Shortcut                       | Description                                                                  |
| ------------------------------ | ---------------------------------------------------------------------------- |
| `consumer`                     | Creates the Consumer widget                                                  |
| `provider`                     | Creates a simple riverod provider                                            |
| `providerFamily`               | Creates a provider with the family modifier                                  |
| `futureProvider`               | Creates a Future provider                                                    |
| `futureProviderFamily`         | Creates a Future Provider with the family modifier                           |
| `streamProvider`               | Creates a Stream provider                                                    |
| `streamProviderFamily`         | Creates a Stream Provider with the family modifier                           |
| `changeNotifierProvider`       | Creates a Change Notifier provider                                           |
| `changeNotifierProviderFamily` | Creates a Change Notifier Provider with the family modifier                  |
| `stateProvider`                | Creates a State provider                                                     |
| `stateProviderFamily`          | Creates a State Provider with the family modifier                            |
| `stateProviderFamily`          | Creates a State Provider with the family modifier                            |
| `stateNotifierProvider`        | Creates a State Notifier provider                                            |
| `stateNotifierProviderFamily`  | Creates a State Notifier Provider with the family modifier                   |
| `scopedProvider`               | Creates a Scoped provider                                                    |
| `stateNotifier`                | Creates a class that extends State Notifier and allows you to edit the types |
| `fClass`                       | Creates a freezed class with freezed annotation                              |
| `fUnion`                       | Creates a freezed union                                                      |
| `fPart`                        | Creates a part statement for the freezed package                             |
| `jPart`                        | Creates a part statement for the json serializable package                   |
| `fJson`                        | Creates a from Json statement for the json serializable package              |
| `toJson`                       | Creates a to Json statement for the json serializable package                |

## Release Notes

### 0.0.2

- Fixed bug in `StreamProvider` and `StateNotifier`.

### 0.0.1

- Initial release of Riverpod and Freezed Snippets for Flutter
