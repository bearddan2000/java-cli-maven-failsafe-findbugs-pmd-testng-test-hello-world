# java-cli-maven-failsafe-findbugs-pmd-testng-test-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testng
framework with failsafe and pmd
plugins.

## Tech stack
- java
- maven
	- findbugs
  - testng
  - failsafe
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
