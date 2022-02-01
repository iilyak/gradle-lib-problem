This is a minimal reproducer for [a question](https://stackoverflow.com/questions/70942703/using-git-dependency-non-gradle-based-project-in-versioncatalogs-using-gradle) I asked on stackoverlow.



I am trying to depend on a specific git version of a scala library. This scala library is build using sbt (therefore it doesn't have build.gradle files in tree).

Is there a way to define a new module so I can refer to it in versionCatalogs?