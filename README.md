<img src="icon.png" align="right" width="180px"/>

# Blueprint


[>> Downloads <<](https://github.com/FabLabsMC/Blueprint/releases)

*Let's get drafting!*

**This mod is open source and under a permissive license.** As such, it can be included in any modpack on any platform without prior permission. We appreciate hearing about people using our mods, but you do not need to ask to use them. See the [LICENSE file](LICENSE) for more details.

This is a template repository for creating Fab Labs projects with automatic CI publishing to the Github Packages maven. Fab Labs projects are typically experimental API drafts that will eventually be PR'd into [Fabric API](https://github.com/fabricmc/fabric).

## Setting Up
Setup is designed to be as easy as possible for creating new projects.
1. Click the "Use this template" button above the file view.
2. Clone the newly-created repo to your computer.
3. In [gradle.properties](gradle.properties), change the `archives_base_name` property to be your mod ID.
4. In your IDE, change the name of the `io.github.fablabsmc.blueprint` package and the `io.github.fablabsmc.blueprint.Blueprint` class as necessary. Change the `MODID` field in `Blueprint` to your mod ID.
5. Change the name of `mixins.blueprint.json` by replacing `blueprint` with your mod ID. Change the value of `package` in the mixins JSON as necessary.
6. In fabric.mod.json, change the `description` and `entrypoints` fields as necessary.
7. You're all set up to get working!
