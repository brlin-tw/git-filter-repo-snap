# Unofficial Snap Packaging for git filter-repo

<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
![(Placeholder) Icon of git filter-repo](https://cdn.staticaly.com/gh/brlin-tw/snapcrafters-template-plus/bea3bc56/snap/gui/git-filter-repo.png "(Placeholder) Icon of git filter-repo")

**This is the unofficial snap for [git filter-repo](https://github.com/newren/git-filter-repo)**, *"Versatile tool for rewriting history of Git repositories"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Status Badge of the `git-filter-repo` Snap](https://snapcraft.io/git-filter-repo/badge.svg)](https://snapcraft.io/git-filter-repo)

<!-- Uncomment and modify this when you have a screenshot
![Screenshot of the Snapped Application](local/screenshots/screenshot.png "Screenshot of the Snapped Application")
-->

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal

    # Install the snap #
    sudo snap install git-filter-repo
    
    # Connect the snap to essential security confinement interfaces #
    ## Allow the application to access files under /media and /mnt ##
    sudo snap connect git-filter-repo:removable-media

    # Launch the application #
    git filter-repo
    snap run git-filter-repo # If you have another existing installation

### The Graphical Way

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/git-filter-repo)

## What is Working

* Removing sensitive text from specified Git repository
* Remove unintentionally committed files from specified Git repository

## What is NOT Working...yet 

Check out the [issue tracker](https://github.com/brlin-tw/git-filter-repo-snap/issues) for known issues.

## Support

* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/brlin-tw/git-filter-repo-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
