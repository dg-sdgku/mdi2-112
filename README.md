# MDI2-112 - Mobile Development II

Official source code repository for **Mobile Development II (MDI2-112)**.

The course is organized into 4 introductory classes focused on Android Wearables development.

## Branch Strategy

This repository uses a simple branch strategy designed for classroom use:

- `main` contains the latest stable completed version of the app.
- `class-*` contains the code used during each lecture.
- `prep/*` contains instructor preparation, testing, and experimentation work.

Development should not happen directly on `main`. Work should be prepared on `prep/*` branches or built during class on `class-*` branches.

## Class Branches

- `class-01-wear-compose-basics`
- `class-02-state-and-interaction`
- `class-03-lists-and-navigation`
- `class-04-final-app`

These branches represent the code used during each class session. Students can review them as references while following the course progression.

## Instructor Preparation Branches

- `prep/class-01`
- `prep/class-02`
- `prep/class-03`
- `prep/class-04`

These branches are for instructor preparation, idea exploration, pre-class testing, and changes that are not yet part of the stable course material.

## Recommended Workflow

1. Prepare or experiment on the `prep/class-XX` branch.
2. Move the completed content to the corresponding `class-XX-*` branch.
3. Use the `class-XX-*` branch during the lecture.
4. After the class is completed, merge the `class-XX-*` branch into `main`.

This keeps `main` as the latest stable version of the project, while the class branches remain clear references for students.
