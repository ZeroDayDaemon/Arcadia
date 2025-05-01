<div class="header" align="center">
<img alt="Arcadia Station" width="500" height="243" src="https://raw.githubusercontent.com/ArcadiaStation/Arcadia/master/Resources/Textures/Logo/logo.png">
</div>

Arcadia Station is a fork of Space Station 14.

[Space Station 14](https://github.com/space-wizards/space-station-14) is a remake of SS13 that runs on [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), a homegrown engine written in C#.
In order to prevent people forking RobustToolbox, a "content" pack is loaded by the client and server. This content pack contains everything needed to play the game on one specific server.

## Arcadia Station Links

[Discord](https://discord.gg/e7mHMrp9EP)

## Space Station 14 Links

<div class="header" align="center">

[Website](https://spacestation14.com/) | [Discord](https://discord.ss14.io/) | [Forum](https://forum.spacestation14.com/) | [Mastodon](https://mastodon.gamedev.place/@spacestation14) | [Lemmy](https://lemmy.spacestation14.com/) | [Patreon](https://www.patreon.com/spacestation14) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone Download](https://spacestation14.com/about/nightlies/)

</div>

## Documentation/Wiki

The [docs site](https://docs.spacestation14.com/) has documentation on SS14's content, engine, game design, and more.
Additionally, see these resources for license and attribution information:
- [Robust Generic Attribution](https://docs.spacestation14.com/en/specifications/robust-generic-attribution.html)
- [Robust Station Image](https://docs.spacestation14.com/en/specifications/robust-station-image.html)

We also have lots of resources for new contributors to the project.

## Contributing

We are happy to accept contributions from anybody. Get in Discord if you want to help. We've got a [list of issues](https://github.com/ArcadiaStation/Arcadia/issues) that need to be done and anybody can pick them up. Don't be afraid to ask for help either!
Just make sure your changes and pull requests are in accordance with the [contribution guidelines](https://docs.spacestation14.com/en/general-development/codebase-info/pull-request-guidelines.html).

We are not currently accepting translations of the game on our main repository. If you would like to translate the game into another language consider creating a fork.

## Building

1. Clone this repo:
```shell
git clone https://github.com/space-wizards/space-station-14.git
```
2. Go to the project folder and run `RUN_THIS.py` to initialize the submodules and load the engine:
```shell
cd space-station-14
python RUN_THIS.py
```
3. Compile the solution:

Build the server using `dotnet build`.

[More detailed instructions on building the project.](https://docs.spacestation14.com/en/general-development/setup.html)

## License

All code for the content repository is licensed under the [MIT license](https://github.com/space-wizards/space-station-14/blob/master/LICENSE.TXT).

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and copyright specified in the metadata file. For example, see the [metadata for a crowbar](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

> [!NOTE]
>Some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.

>New assets are requested to be licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) if you have the appropriate rights to license them as such.

>Arcadia Station [logo assets](https://github.com/ArcadiaStation/Arcadia/Resources/Textures/Logo) and the name "Arcadia Station" are copyrighted and are not under a permissive license.
