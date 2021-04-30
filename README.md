# Repository for docker images i need for ci builds

## node-git-mvn
Image based on ubuntu:20.04 with 
* nodejs 12 (for semantic-release)
* git for semantic-release to interact with git-repositories
* java openjdk-11 for maven builds
* maven

## java-docker
Image based on azul/zulu-openjdk:15.0.2 with added docker installation

Used for gradles bootBuildImage functionality (needs docker daemon)
