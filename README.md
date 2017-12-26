# SA:MP Attachment Editor

A SA:MP tool for editing character-attached objects in-game. Save coordinates to a file for usage in a gamemode.

## Usage

To use the browser, simply clone this repo, ensure, build and run the package:

```bash
sampctl package run --forceBuild --forceEnsure
```

And connect to `localhost:7777`.

## As a Filterscript

If you want to load the tool as a filterscript, sampctl is yet to provide an easy way to work with filterscripts so the workaround is simply to build the package as normal:

```bash
sampctl package build
```

Then copy the .amx to your server and add to the `filterscripts` section in `samp.json`/`samp.yaml` - or load during runtime via `rcon loadfs attachedit`.
