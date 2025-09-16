# ComposeReduxKit

ComposeReduxKit is a sample application that shows what a redux-like implementation of actions, reducer, and global state might look like in Kotlin Compose Multiplatform.

## Requirements

- **Kotlin**: >1.8.20
- **Java**: >8+ (JVM target)
- **JetBrains Compose**: 1.4.1

## Run

```bash
./gradlew run
```

## Package

Creates native packages for macOS (.dmg), Windows (.msi), and Linux (.deb):

```bash
./gradlew package
```

Output files are located in `build/compose/binaries`.
