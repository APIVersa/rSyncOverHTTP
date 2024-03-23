# rSyncOverHTTP
A script to mirror a file server over HTTP, optionally downloading only newer files or files that do not already exist, and supporting resumable downloads.

# TODO:
- Update owner info to the one that ran the script
- Add flag for user-agent
- Add more flags and optional usage criteria

# Installation:
## Step 1: wget the file to /usr/bin
sudo wget [https://raw.githubusercontent.com/APIVersa/rSyncOverHTTP/main/rsyncoverhttp](https://raw.githubusercontent.com/APIVersa/rSyncOverHTTP/main/rsyncoverhttp) -O /usr/bin/rsyncoverhttp
## Step 2: chmod +x the file
sudo chmod +x /usr/bin/rsyncoverhttp
## Step 3: use rsyncoverhttp command to run your commands
rsyncoverhttp --help
