Pidgin usually stores passwords as plaintext. This plugin instead saves all passwords to the gnome keyring, which some would argue is a more secure form of password storage.

After the plugin is enabled, whenever an account with a pidgin-stored password signs on, its password will automatically be saved to the keyring and removed from the plaintext accounts.xml file. A few bugs have been recently fixed. The plugin will no longer prompt the user for a password on startup on some systems.

The plugin is available as a ppa for Ubuntu: [ppa:pidgin-gnome-keyring/ppa](https://launchpad.net/~pidgin-gnome-keyring/+archive/ppa).
Other binary builds are available at the project's [Downloads page](http://code.google.com/p/pidgin-gnome-keyring/downloads/list).
See the [InstallationInstructions](https://code.google.com/p/pidgin-gnome-keyring/wiki/InstallationInstructions) page for more details.

NOTE: This plugin will not be able to prevent other plugins from writing passwords to accounts.xml 
