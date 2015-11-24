# Cachet for OpenShift 
[![OpenShift](http://launch-shifter.rhcloud.com/launch/Cachet On.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/tengyifei/openshift-cartridge-nginx-hhvm&cartridges%5B%5D=mysql-5.5&initial_git_url=https://github.com/ALinuxNinja/openshift-cachet.git&name=cachet&initial_git_branch=1.x-HHVM)

This installs the legacy 1.x version of Cachet

Cachet for OpenShift automatically downloads the latest version of Cachet v1 and installs it in a HHVM based setup.

## IMPORTANT
This no longer works due to https://github.com/tengyifei/openshift-cartridge-nginx-hhvm/issues/31
The code is here for legacy purposes only.

## Migrating
It is possible to migrate from the old HHVM setup to the PHP-FPM setup (new).

 1. Find the version of Cachet you are using. The version is usually indicated by a file with the version as it's name in $OPENSHIFT_DATA_DIR. The version should be something like "1.2.3"
 2. Run the following (replace the version 1.2.3 below with your version) `echo "1.2.3" > ~/.env/user_vars/CACHET_VERSION`
 3. Get the latest mgmutil script from https://raw.githubusercontent.com/ALinuxNinja/openshift-cachet/1.x/.openshift/data/mgmutil . You can download it into $OPENSHIFT_DATA_DIR/bin. Make it executable.
 4. Run mgmutil, and select backup.
 5. Download the backup, and go to the 1.x branch of this repo.
 6. Follow the instructions on the repo to restore a backup.

I highly suggest not removing the old app until the new deployment is confirmed to be working.

## How to install
To install, just click the OpenShift button above.

## Upgrading
There is an experimental script called 'upgrade' in $OPENSHIFT_DATA_DIR/bin
Note that the script is experimental and may cause issues with your installation.

## Versions
Please change the branch to the major version of cachet that you want to install.
If it doesn't exist, it isn't supported yet.
