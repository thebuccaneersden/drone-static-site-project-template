# drone-static-site-project-template
This is a template for a static site project that integrates with DroneCI

This project assumes that you simply want to host a static website and that it deploys to production when merges are made into the master branch.

On deployment, it cleans up a few files and then rsync's the remaining files to a remote server. This is configuration you need to add to the deploy step in the .drone.yml file.