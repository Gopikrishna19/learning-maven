## Goals or commands are predefined plugins

eg: clean, compile, test, package, install, deploy

 - defined in super pom and inherited to each packages
 - can be tuned to current project

## Phases are plugins of maven that the goals are tied to

 - validate: validate the dependencies and all other information
 - compile: compile the code
 - test: test the compiled code
 - package: packs the code into defined output, like JAR
 - integration-test: deploy and run tests (new from v3)
 - verify: check integrity of package
 - install: install to local repo
 - deploy: install to remote repo
