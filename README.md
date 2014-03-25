Personal website
================

This is the source of my personal website.

## Build and push to Github Pages

First configure the `grunt-build-control` options to point to the correct remote repository.

Run the following command to build the project and push to `gh-pages` branch

	grunt buildpages
	
This will first run the `build` task and then `buildcontrol:pages` task and push it to the remote repository.