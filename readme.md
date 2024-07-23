# yarr-ng

**yarr-ng** (yet another rss reader, next generation) is a web-based feed aggregator which can be used both
as a desktop application and a personal self-hosted web-server for a single user.

This is a next generation fork of the amazing [yarr](https://github.com/nkanaev/yarr) RSS reader by [nkanaev](https://github.com/nkanaev/). 

yarr-ng hopes to build on the original repo's excellent base, and add some quality of live improvements. The upstream yarr's repo is deemed feature complete, and so improvements are few and far between. This project is for those who want a liitle more out of yarr.


## yarr-ng todo

Done tasks are changes from the upstream yarr repo.

- [x] fork
- [ ] improve readme
- [ ] docker setup
- [ ] auto build and publish
- [ ] improve docs
- [ ] enlarge mobile UI
- [ ] error feedback
- [ ] flatpak?
- [ ] pikapod?


## architecture

The app is a single binary with an embedded database (SQLite).

![screenshot](etc/promo.png)


## usage

The latest prebuilt binaries for Linux/MacOS/Windows AMD64 are available
[here](https://github.com/nkanaev/yarr/releases/latest). Installation instructions:

* MacOS

  Download `yarr-*-macos64.zip`, unzip it, place `yarr.app` in `/Applications` folder, [open the app][macos-open], click the anchor menu bar icon, select "Open".

* Windows

  Download `yarr-*-windows64.zip`, unzip it, open `yarr.exe`, click the anchor system tray icon, select "Open".

* Linux

  Download `yarr-*-linux64.zip`, unzip it, place `yarr` in `$HOME/.local/bin`
and run [the script](etc/install-linux.sh).

[macos-open]: https://support.apple.com/en-gb/guide/mac-help/mh40616/mac

For self-hosting, see `yarr -h` for auth, tls & server configuration flags.

See more:

* [Building from source code](doc/build.md)
* [Fever API support](doc/fever.md)

## credits

[Feather](http://feathericons.com/) for icons.
