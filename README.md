## WHAT
Creates the 'base' container for Open-Publisher. It starts with my custom docker-TeXlive container and then installs various dependencies, ruby, Pandoc, Jekyll, and Kindlegen.

This container is meant to be used as the starting/base container for [Open-Publisher](https://github.com/chrisanthropic/Open-Publisher). (See the Dockerfile in the Open-Publisher repo for more info)

## HOW
1. Git clone this repo.
2. Build the container.
  - `docker build -t open-publisher-base .`
