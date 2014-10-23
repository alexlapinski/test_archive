# Test Archive Repository

This repository exists for the sole purpose of testing archival of git repositories from github.com.

## How
1. cd into the location you want to archive this repo to
2. run the command ```git clone --mirror <repo-endpoint>```
3. Done
 
## Restore / Use Archive
You can always get back to the archived repository by using the location on disk, from step 1 above as the git remote.
All of the branches from the github repo should be present, so just treat it as a remote on disk (shared drive, etc.).
