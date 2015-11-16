# Cachet for OpenShift [![OpenShift](http://launch-shifter.rhcloud.com/launch/LAUNCH ON.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/boekkooi/openshift-cartridge-nginx&cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/boekkooi/openshift-cartridge-php&cartridges%5B%5D=mysql-5.5&initial_git_url=https://github.com/ALinuxNinja/openshift-cachet.git&name=cachet&initial_git_branch=1.x)

This installs the legacy 1.x version of Cachet

Cachet for OpenShift automatically downloads the latest version of Cachet v1 and installs it in a PHP-FPM based setup.

## How to install
To install, just click the OpenShift button above.

## Upgrading
There is an experimental script called 'upgrade' in $OPENSHIFT_DATA_DIR/bin
Note that the script is experimental and may cause issues with your installation.

## Versions
Please change the branch to the major version of cachet that you want to install.
If it doesn't exist, it isn't supported yet.
