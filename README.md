# Now maintained by Carpa1l 

Not supporting the rblx file...

# Commander Reborn

Comander Reborn is an continuation of Commander 4 made by Va1kio, It will include (currently) everything that was originally made by Valkio.

# Documents

Inside our documents you can see how to use the API, Guides and more for you to use if your stuck at any point!



## Installing

There's a few ways to install Commander. If you prefer working with the source code, consider using [Rojo](#Rojo). If you only want to install Commander, use the [loader](#Loader).

### Rojo

If you are syncing with Rojo, download the newest source code inside the Releases section, and then run the following command in your terminal application (Assume you are inside the folder of the source code)
```
rojo build -o "release.rbxlx"
```
And then, open `release.rbxlx` in Roblox Studio and start the Rojo server.
```
rojo serve
```

### Loader

For your convenience, we've also released Commander as a loader, which allows Commander to be always up-to-date and easier to manage. You can find the download link [here](https://www.roblox.com/library/6829537547/Commander-Reborn). Place the loader inside `ServerScriptService` for high maintainability and maximum security.

## Contributing

Commander adheres the Contributor Covenant [code of conduct](./CODE_OF_CONDUCT.md). By contributing, you are expected to uphold this project. Report any inappropriate behavior in our Discord server.

If you are creating your first time issue or pull request to this repository, consider reading our [contributing guidelines](./CONTRIBUTING.md).

Before starting to contribute, please clone this repository with command `git clone https://github.com/va1kio/commander.git` and install Commander with the [Rojo](#Rojo) method, which will allow you to do testing.

Once you have finished making changes to the codebase, please group changes and stage them one by one with a clear and descriptive commit message, and create a pull request.

## Credits

Commander is built with open sourced libraries and codes, a list of them can be found here:
- [Promise](https://github.com/evaera/roblox-lua-promise)
- [MockDataStore](https://github.com/buildthomas/MockDataStoreService)
- [Matcher](https://github.com/rgieseke/textredux/blob/main/util/matcher.lua)
- [Snapdragon](https://github.com/roblox-aurora/rbx-snapdragon)

## License
[MIT](./LICENSE)
