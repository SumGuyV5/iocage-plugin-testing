# iocage-plugin-testing

Install a plugin by running a this command...

iocage fetch -P /the/directory/path/<file_name>.json

where btfs.json is the name of the plugin you wish to install and test.

If you are running the command the same directory as the plugin json files, you don't need to add the path.

If you are testing on FreeNAS core the install plugin will show up in the Plugins ui, but will not have a icon.

If you wish to use the settings options to get or set.

iocage get -P <option> <jail> and iocage set -P <option=value> <jail>
