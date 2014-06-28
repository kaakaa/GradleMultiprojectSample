Gralde Multiproject Sample
==========================

This projects is sample projects for gradle multiproject build.

The goal is completion building App project.
App project depends on Stab project.

Structure
=========

```
├── App               <=    Build target
│   └── src
│       ├── main
│       │   └── java
│       │       └── Library.java
│       └── test
│           └── java
│               └── LibraryTest.java
├── README.md
└── build
    ├── build.gradle   <=   Main build script
    ├── dep_project
    │   └── Stab       <=   Dependency target
    │       └── src 
    │           └── main
    │               └── java
    │                   └── sample
    │                       └── Stab.java
    └── settings.gradle
```
