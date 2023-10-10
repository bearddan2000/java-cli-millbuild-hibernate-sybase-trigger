# java-cli-millbuild-hibernate-sybase-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- millbuild
  - hibernate
  - hql
  - envers
  - log4j
  - sybase driver

## Docker stack
- nightscape/scala-mill
- datagrip/sybase

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
