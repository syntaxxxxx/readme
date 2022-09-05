## 🛠 Tech Stacks

- Kotlin.
- [Kotlin DSL](https://docs.gradle.org/current/userguide/kotlin_dsl.html).
- [Jetpack Compose](https://developer.android.com/jetpack/compose).
- [Coroutines](https://kotlinlang.org/docs/coroutines-overview.html).
- Android Jetpack
  - [Compose](https://developer.android.com/jetpack/compose?gclid=CjwKCAjwvNaYBhA3EiwACgndguAbK-Q9IVtJx1wkM85Nt-pI5JMCRKTD4O-wPeu-vyLBxFhkB6XESBoClKQQAvD_BwE&gclsrc=aw.ds).
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel?gclid=CjwKCAjwvNaYBhA3EiwACgndgjUoa6vdlcCNKAF9x1TQVGibh7eKA2BieACmNWUhWw2Sr-Fo37glTRoCH20QAvD_BwE&gclsrc=aw.ds).
  - [Navigation Component](https://developer.android.com/guide/navigation?gclid=Cj0KCQjwmdGYBhDRARIsABmSEeO1MpKCj6KtTR3A6AHdrUEPq80CEvj3J7PbWADTdMGd4_6Sz6lxYW4aAs-5EALw_wcB&gclsrc=aw.ds).
  - [Room Database](https://developer.android.com/jetpack/androidx/releases/room?gclid=Cj0KCQjwmdGYBhDRARIsABmSEeP5InkhjXrGeyQ6tMQhtSWktfRdwHaOoxRRQ7dAPRhmVzNJ8eAcwO4aAtYdEALw_wcB&gclsrc=aw.ds).
- [Retrofit](https://github.com/square/retrofit).
- [Retrofit Adapters](https://github.com/skydoves/retrofit-adapters).
- [Moshi](https://github.com/square/moshi).
- [Hilt](https://dagger.dev/hilt/).
- [KSP](https://github.com/google/ksp).
- [Timber](https://github.com/JakeWharton/timber).

## 🏛️ Modular Architecture Design

## 🏛️ Architecture

## 🏛️ Project Structure

**`core`**:

**`network`**:

**`database`**:

**`ui`**:

* `feature`
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
      - `[ClassName]Screen`
      - `[ClassName]ViewModel`
