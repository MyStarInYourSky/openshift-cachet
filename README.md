# Cachet for OpenShift [![OpenShift](https://raw.githubusercontent.com/pcon/sticky-notes-quickstart/master/public/openshiftDeploy.png)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/boekkooi/openshift-cartridge-nginx&cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/boekkooi/openshift-cartridge-php&cartridges%5B%5D=mysql-5.5&initial_git_url=https://github.com/ALinuxNinja/openshift-cachet.git&name=cachet&initial_git_branch=staging)

This is the staging edition.

Cachet for OpenShift automatically downloads the latest release of Cachet and installs it in a HHVM based setup.

## How to install
To install, just click the OpenShift button above.

## Upgrading
There is an experimental script called 'upgrade' in $OPENSHIFT_DATA_DIR/bin
Note that the script is experimental and may cause issues with your installation.

## Warning
This repo does not work with Cachet v2, work is being done to make it compatible.
At this time, the repo will download the latest v1 version only.
