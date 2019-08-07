[![Go Report Card](https://goreportcard.com/badge/github.com/Luzifer/wiki)](https://goreportcard.com/report/github.com/Luzifer/wiki)
![](https://badges.fyi/github/license/Luzifer/wiki)
![](https://badges.fyi/github/downloads/Luzifer/wiki)
![](https://badges.fyi/github/latest-release/Luzifer/wiki)
![](https://knut.in/project-status/wiki)

# Luzifer / wiki

`wiki` is a small file-based Wiki implementation with web-editing capabilities and a Git backed storage for history of pages.

The goal of this project was to have a small application to be deployed without any dependencies to open a Wiki for note taking or documentation purpose. 

The software itself has no concept of users or authentication and is held as simple as possible. Saved pages are stored as plain Markdown file onto the local disk inside a Git repository which on the one hand can be used to backup the state (just add a remote and set up a cron to push changes) and on the other hand to recover contents if someone deleted contents from a page.