# iocage-plugin-testing

Install a plugin by running a this command...

```sh
iocage fetch -P <plugin_name> -g https://github.com/SumGuyV5/iocage-plugin-testing.git --update
```
or for a list of plugins
```sh
iocage fetch --plugins -g https://github.com/SumGuyV5/iocage-plugin-testing.git --update
```

If you are testing on FreeNAS core the installed plugin will show up in the Plugins ui, but will not have a icon.

If you wish to use the settings options to get or set.

```sh
iocage get -P <option> <jail> or iocage set -P <option=value> <jail>
```
