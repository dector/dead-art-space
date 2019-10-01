---
title: Notes App | 0. Getting started
createdAt: 29-09-19
tags: devlog, notes app, android
isDraft: true
---

This blog-post series gonna highlight my process of building Android app in modern (2k19) technologies. **This notes are simple dev-log** and not describe (usually) best practices, but are the reflection on the process itself.

## Stages

0. [Getting started](#).
1. Planning v1.
2. Milestone 1 (v0.3): Shitty MVP.
3. Milestone 2: (v0.4): Material Design.
4. Milestone 3: (v0.4.1): UI Testing.
5. Milestone 4: (v0.5): Refactoring.

## Project description

This is native note-taking android app built with [Android SDK](https://d.android.com) using [Kotlin](https://kotlinlang.org) programming language and [Material](https://material.io) design system.

### Tech-stack

#### Current stack.

- [Android SDK](https://d.android.com), [Android Jetpack](https://d.android.com/jetpack).
- [Gradle](https://gradle.org) build tool.
- [Kotlin](https://kotlinlang.org), Kotlin [coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html).
- [Material](https://material.io/develop/android) components.

#### Code/product design focus/decisions for v1.

- Quality product (judged by my personal taste).

- Testability: UI and Unit testing.
- Good looking UI (based on Material Design System).
- Exploration of best UX practices.
- Clean and elegant code.
- [Clean](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)-ish architecture.
- MVI for presentation layer.

#### Tools.

- **IDE**: [Android Studio](https://d.android.com/studio) (based on awesome [Intellij IDEA](https://jetbrains.com/idea)).

- Repository: [Github](https://github.com/dector/notes-app) (private yet).

#### Features.

- Taking notes.
- Editing existing notes.
- Colored notes.
- Archive, Trash Bin.