OOO Maven Repository
====================

This repository hosts Maven artifacts for various libraries on which OOO libraries depend, but
which we could not find a reliable public Maven repository. The OOO libraries which depend on
libraries in this repo will already contain build configuration to reference this repository as
needed.

If you want to reference any libraries hosted here yourself, add the following to your `pom.xml`:

    <repositories>
      <repository>
        <id>ooo-repo</id>
        <url>https://raw.githubusercontent.com/threerings/maven-repo/master/repository</url>
      </repository>
    </repositories>

Questions
---------

Questions, comments, etc. can be directed to the [Three Rings Libraries] Google Group.

[Three Rings Libraries]: http://groups.google.com/group/ooo-libs
