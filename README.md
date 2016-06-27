# mantis-to-redmine
Mantis to Redmine Import functionality

### About

In the current Redmine `3.3.x` Version the Mantis-to-Redmine importer doesn't work with the current stable Mantis `1.2.19` version, due to different table settings and maybe and not really supported code update from the redmine devs.

> I'm not a ruby expert, to be honest it will be my first ruby project - feel free for enhancement comments! Thanks

### Installation

In this repository you only get the current `migrate_from_mantis.rake` file. So to install the working solution you have to just copy the file into the redmine directory: `redmine/lib/tasks`
> Take care of making a local copy of the original file

- The current redmine version, and so this version is only working for a **clean** readmine installation.
	- I'll try to look into it after some other issues.

- The initial commit will be the original file from redmine after a clean installation. To keep it in memory.

### Current status: June 27, 2016

It is working with exceptions as seen on the issue page.
My first goal will be a solid import from the above pointed version.


### ToDo

- A clean redmine installation is no longer necessary to import from mantis.
- Previous mantis versions had different table structures - include an config to allow import from older mantis versions.
- Mantis `1.3.0` is about to get released (current RC2 status [June 27, 2016]) - include it.
- If there will be enough feedback for an import functionality for older redmine versions, I will look into it.

### LICENSE

to keep it short: Original code is GPL v2 - I'll update it here with GPL v3.

### CREDITS

Redmine and it's contributors.