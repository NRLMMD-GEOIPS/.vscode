    # # # Distribution Statement A. Approved for public release. Distribution unlimited.
    # # #
    # # # Author:
    # # # Naval Research Laboratory, Marine Meteorology Division
    # # #
    # # # This program is free software: you can redistribute it and/or modify it under
    # # # the terms of the NRLMMD License included with this program. This program is
    # # # distributed WITHOUT ANY WARRANTY; without even the implied warranty of
    # # # MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the included license
    # # # for more details. If you did not receive the license, for more information see:
    # # # https://github.com/U-S-NRL-Marine-Meteorology-Division/

# .vscode
Settings for a consistent GeoIPS VSCode Workspace

This repository can be used in two ways. If you are editing a single repository,
it can be cloned directly into that repository. If you are editing multiple
repositories, it can be cloned parallel to your repositories, and used for WorkSpace
level VSCode settings across all GeoIPS plugins.

## Working with a single repository
If you are editing a single repository:
- Clone your repository anywhere
- Change directories to your repository
- Clone this repository into your repository's directory
  ```
  git clone git@github.com:NRLMMD-GEOIPS/.vscode.git
  ```
- Open your repository in VSCode

## Working with multiple repositories
If you are editing multiple repositories (e.g. multiple plugins or a plugin plus
GeoIPS itself) you can ensure that all plugin repositories will use the same linting
and formatting settings within VSCode by doing the following: 
- Clone all of the repositories that you are working on into a single directory
  (e.g. `$GEOIPS_PACKAGES_DIR`)
- Clone .vscode into that same directory (e.g.
  `git clone git@github.com:NRLMMD-GEOIPS/.vscode.git $GEOIPS_PACKAGES_DIR/.vscode`)
- Open the directory that contains all repositories in VSCode.
