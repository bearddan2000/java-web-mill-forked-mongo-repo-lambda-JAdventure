# java-web-mill-spring-forked-mongo-repo-lambda-JAdventure

## Description
A POC for REST web service using mongodb.
Creates a user with credentials.

Uses spring's mongorepository
with a query using lambda collectors.

## Tech stack
- java
- mill
  - mongo connector
  - spring
- mongo

## Docker stack
- mongodb:latest
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`
- Endpoints
  - localhost/weapons/
  - localhost/weapons/name/shiv

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Data from JAdventure text game](https://github.com/Progether/JAdventure.git)
- [Code concept](https://github.com/ragcrix/StudentInformationSystem.git)
