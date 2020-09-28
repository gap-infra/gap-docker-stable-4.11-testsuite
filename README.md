[![Build Status](https://travis-ci.com/gap-infra/gap-docker-stable-4.11-testsuite.svg?branch=master)](https://travis-ci.com/gap-infra/gap-docker-stable-4.11-testsuite)

# gap-docker-stable-4.11-testsuite

This repository is used to run GAP test suite using the Docker container
with GAP from the tip of the stable-4.11 branch and packages from the archive
https://www.gap-system.org/pub/gap/gap4pkgs/packages-stable-4.11.tar.gz

This Travis test allows everyone (not only to those who can access Jenkins)
to see how testinstall/standard/bugfix behaves with no packages, with default
packages, and with all packages loaded, using the GAP Docker container for
the stable-4.11 branch with packages from the `packages-stable-4.11.tar.gz` archive.

This is Travis CI cron job, scheduled to run daily.

For the full list of all publicly available tests from the GAP test suite
see https://github.com/gap-system/gap-distribution/blob/master/README.md
