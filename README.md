## 🛠 Tech Stacks & Open Source Libraries

- Kotlin Language.
- Minimum SDK level 21.
- [Kotlin DSL](https://docs.gradle.org/current/userguide/kotlin_dsl.html).
- [Jetpack Compose](https://developer.android.com/jetpack/compose).
- [Coroutines](https://github.com/Kotlin/kotlinx.coroutines)
- [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-
- Android Jetpack
  - Compose: Android’s modern toolkit for building native UI.
  - ViewModel: UI related data holder and lifecycle aware.
  - [Navigation Component](https://developer.android.com/guide/navigation?gclid=Cj0KCQjwmdGYBhDRARIsABmSEeO1MpKCj6KtTR3A6AHdrUEPq80CEvj3J7PbWADTdMGd4_6Sz6lxYW4aAs-5EALw_wcB&gclsrc=aw.ds) for injecting dependencies.
  - [Room Database](https://developer.android.com/jetpack/androidx/releases/room?gclid=Cj0KCQjwmdGYBhDRARIsABmSEeP5InkhjXrGeyQ6tMQhtSWktfRdwHaOoxRRQ7dAPRhmVzNJ8eAcwO4aAtYdEALw_wcB&gclsrc=aw.ds).
- [Dependency Injection => Hilt](https://dagger.dev/hilt/).
- [Retrofit2 & OkHttp3](https://github.com/square/retrofit).
- [Retrofit Adapters](https://github.com/skydoves/retrofit-adapters).
- [Moshi](https://github.com/square/moshi).
- [KSP](https://github.com/google/ksp).
- [Timber](https://github.com/JakeWharton/timber).

## 🏛️ Modular Architecture Design

## 🏛️ Architecture

## 🏛️ Project Structure

**`core`**:
**`network`**:
**`database`**:
**`ui`**:

* `feature A`
  - `data`
      - `services`
      - `entity`
      - `source`
        - `remote`
        - `local`
  - `domain`
      - `entity`
      - `repository`
      - `usecase`
  - `presentation`
      - `entity`
