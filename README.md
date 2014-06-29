Gralde Multiproject Sample
==========================

This projects is sample projects for gradle multiproject build.

The goal is completion building App project.
App project depends on Stab project.

Structure
---------

```
├── App  <=  Build target project
│   └── src
│       ├── main
│       │   └── java
│       │       └── Library.java
│       └── test
│           └── java
│               └── LibraryTest.java
├── BuildScript
│   ├── build.gradle  <=  Main build script
│   ├── lib_svnant
│   └── settings.gradle
├── README.md
└── svn_repo  <=  include Stab project
```

Build Command
-------------

```
gradle -b BuildScript/build.gradle :App:build
```

on root.

License
=======

This project include *Apache SvnAnt*.
And *SvnAnt* use JavaHL and SVNkit.

Their licenses is below.

* [SvnAnt license](http://subclipse.tigris.org/svnant/svn.html "SvnAnt license)
* [and other licenses](https://github.com/kaakaa/GradleMultiprojectSample/tree/master/BuildScript/lib_svnant "and other licenses")
