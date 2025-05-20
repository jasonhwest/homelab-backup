# Usage

1. Create a folder under ~/backup with the same name of the Docker container
1. cd into your new ~/backup/DOCKER_CONTAINER folder
1. Create softlinks for each folder and file you wish to backup. Note that backing up media and secrets is not advised.
1. Commit the changes to GitHub to retain a backup image of your Docker containers.
1. Make sure that you also backup your .env files in Bitwarden
