msdeploy-package-publish is a set of targets intended to add support for publishing packages to the Web Publishing Pipeline

This project was an experiment in how an MSBuild-focused package publish could work. Since creating this prototype, my general recommendation has changed to publishing MSDeploy packages using the msdeploy.exe command line (or API for advanced scenarios) as it grants access to advanced feautured not available to MSBuild, like ".publishsettings" and Credential Vault for storing deployment credentials.
