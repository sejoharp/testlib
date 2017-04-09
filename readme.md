# test lib
the purpose of this repo is find out how easy it is to host maven artefacts

## deploy new version
1. set the version in pom.xml file.

    SNAPSHOT will build a new snapshot version

    delete SNAPSHOT will build a new release
1. `mvn deploy`
1. `git add`
1. `git commit`
1. `git push`
