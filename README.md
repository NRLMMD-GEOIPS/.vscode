    # # # This source code is subject to the license referenced at
    # # # https://github.com/NRLMMD-GEOIPS.

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
