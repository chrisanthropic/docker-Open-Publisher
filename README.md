## WHAT
Creates the 'base' container for Open-Publisher. It starts with my custom docker-TeXlive container and then installs various dependencies, ruby, Pandoc, Jekyll, and Kindlegen.

## HOW
1. Git clone this repo.
2. Build the container.
  - `docker build -t open-publisher-base .`
