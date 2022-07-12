# LU Chess

Discord bot for Laurentian University Chess Club (not yet founded)
Could possibly reconfigure for use outside. 

# Plans

## Tournament Creation

This bot will have the ability to create tournaments regularly depending on configuration (or hard coded for testing/if we can't figure it out)

## Notifications

When tournaments are created or nearly started, will have the capability to ping everyone (or possibly a group) about the tournament. 

## Tournament Imports

With lichess, importing tournament files is possible, this will hopefully be a feature, such that when tournaments are done, the tournament PGN and game tables will be able to be imported. This can be used for analysis. 

# Python Version and Requirements

Currently running Python 3.8.10 on Ubuntu 20.04, keep this in mind when creating the environment. All used requirements are in requirements.txt, .gitignore currently ignores .env which is the location of the python environment. 