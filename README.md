# rSyncOverHTTP
A script to mirror a file server over HTTP, optionally downloading only newer files or files that do not already exist, and supporting resumable downloads.

# TODO:
- Update owner info to the one that ran the script
- Add more flags and optional usage criteria

# Installation:
## wget the file to /usr/bin
wget file_url -O /usr/bin/rsyncoverhttp
## chmod +x the file
chmod +x /usr/bin/rsyncoverhttp
## use rsyncoverhttp command to run your commands
rsyncoverhttp --help
