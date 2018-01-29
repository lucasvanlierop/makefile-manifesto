# makefile-manifesto
A number of guidelines on how to write proper makefiles in the modern world of web development

## Targets should have a single responsibility
A target should contain rules related to just one target

## Targets should be a file if possible (Avoid `.PHONY`)
Make is meant to create files and is very good at determining if they should be recreated or not, make use it!

## All target pre-requisites should be ..
