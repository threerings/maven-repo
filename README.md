OOO Maven Repository
====================

This repository hosts Maven artifacts for various OOO libraries (Narya, Nenya,
Vilya, etc.). The individual projects will likely have instructions on adding
this repository to your Maven configuration so that you can fetch artifacts
from it, but we'll repeat them here for fun and profit.

Add the following `<repositories>` section to your `pom.xml` (or merge it in
with any such existing section):

    <repositories>
      <repository>
        <id>ooo-repo</id>
        <url>http://threerings.github.com/maven-repo</url>
      </repository>
    </repositories>

You can then add dependencies on OOO artifacts to your heart's content.

Questions
---------

Questions, comments, etc. can be directed to the [Three Rings
Libraries](http://groups.google.com/group/ooo-libs) Google Group.
