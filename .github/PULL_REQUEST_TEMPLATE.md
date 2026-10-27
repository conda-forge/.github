<!--
Thank you for your pull request.
Below are a few things we ask you kindly to self-check before getting a review. Remove checks that are not relevant.
-->
Checklist
* [ ] Used a [personal fork of the feedstock to propose changes](https://conda-forge.org/docs/maintainer/updating_pkgs.html#forking-and-pull-requests)
* [ ] Bumped the build number (if the version is unchanged)
* [ ] Reset the build number to `0` (if the version changed)
* [ ] [Re-rendered]( https://conda-forge.org/docs/maintainer/updating_pkgs.html#rerendering-feedstocks ) with the latest `conda-smithy` (Use the phrase <code>@<space/>conda-forge-admin, please rerender</code> in a comment in this PR for automated rerendering)
* [ ] Ensured the license file is being packaged.
* [ ] Checked that this change (e.g. adding a new platform or bumping a pinned dependency) is not already being handled by a [platform migration](https://github.com/conda-forge/conda-forge-pinning-feedstock/tree/main/recipe/migration_support) or a [pinning migration](https://github.com/conda-forge/conda-forge-pinning-feedstock/tree/main/recipe/migrations). If one exists, make sure this feedstock is included in it (e.g. listed in the platform migration's `.txt` file, or shown on the [migration status page](https://conda-forge.org/status/)) instead of making the change here.

<!--
Please note any issues this fixes using [closing keywords]( https://help.github.com/articles/closing-issues-using-keywords/ ):
-->

<!--
Please add any other relevant info below:
-->
