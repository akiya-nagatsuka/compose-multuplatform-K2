Steps to reproduce the bug with K2:
1. Use the [default template](https://github.com/JetBrains/compose-multiplatform-template) to create Compose Multiplatform Project
2. Change Kotlin version to 1.9.0-Beta
3. Add Compose compiler compatible with Kotlin 1.9.0-Beta
4. Remove iOS source set (because of some build issue)
5. Add `kotlin.experimental.tryK2=true` flag in properties
6. Sync and build the project.