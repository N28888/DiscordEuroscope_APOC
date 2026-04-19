# APOC DiscordEuroscope
A plugin written to provide Discord Rich Presence for EuroScope, branded for APOC.
And the good news is that it supports both ES *3.1d* and *3.2*!

All you need is to *load the plugin*, and it'll work!
You can download the plugin from the Releases page. Or compile it yourself using Visual Studio.

By default, the generated `DiscordEuroscope_config.json` uses the APOC Discord application ID, the `apoc_logo` large image asset, no small image asset, and no Rich Presence buttons. If a config file already exists next to the DLL, update that file or delete it so the plugin can regenerate the new defaults.

**Please** report any bugs in the issues section of this repository.

# Radio Callsigns file example:
```
HECC_CTR Cairo Radar
HECA_APP Cairo Director
```
