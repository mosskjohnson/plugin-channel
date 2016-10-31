# Micro Official Plugin Channel

This repository contains the 'channel.json' file which lists all official micro plugins. This is where the editor looks to search for plugins to install.

## Plugins

| Plugin      | Description                                           | Link                                                |
| ----------- | ----------------------------------------------------- | --------------------------------------------------- |
| `snippets`  | Provides snippets functionality                       | https://github.com/boombuler/microsnippets          |
| `go`        | Provides `gofmt` and `goimports` support for Go files | https://github.com/micro-editor/go-plugin           |
| `fish`      | Provides `fishfmt` support for Fish files             | https://github.com/onodera-punpun/micro-fish-plugin |
| `wc`        | Plugin to count words/characters                      | https://github.com/adamnpeace/micro-wc-plugin       |

## Adding your own plugin

To add your own plugin, create a `repo.json` file containing all the metadata information for your plugin. See the Go plugin [repo.json](https://github.com/micro-editor/go-plugin/blob/master/repo.json) file as an example.

Then you can open a pull request which adds the link to that file to the `channel.json` file in this repo.
