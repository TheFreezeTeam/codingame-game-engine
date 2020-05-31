# About

This is the Game Engine Toolkit of CodinGame. With it one can develop a game for the [CodinGame platform](https://www.codingame.com).

This engine is meant to be imported with maven from a project such as [the Game Engine skeleton](https://github.com/CodinGame/game-skeleton).

# Getting started

Check the documentation on the [tech.io playground](https://www.codingame.com/playgrounds/25775).

Check the [javadoc](https://codingame.github.io/codingame-game-engine/).

# Building

## Requirmentes
* maven
* ojdk (Open JDK)
* gpg

Commands to install or update requirments on windows using Chocolatey
```
cup maven
cup ojdkbuild11
cup gpg4win
```
## Configuration

### Create GPG Key Pair with Kleopatra

File -> New Key Pair

Save Passphrase.

## Build

`mvn clean install`