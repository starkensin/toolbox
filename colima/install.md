
## install docker

`brew install docker docker-compose`

```sh
Compose is a Docker plugin. For Docker to find the plugin, add "cliPluginsExtraDirs" to ~/.docker/config.json:
  "cliPluginsExtraDirs": [
      "/opt/homebrew/lib/docker/cli-plugins"
  ]
```

## install colima

```sh
softwareupdate --install-rosetta
brew install colima 
brew services start colima
```

`colima start --edit`

```
vmType: vz
rosetta: true
mountType: virtiofs
```




c.f. https://marczin.dev/blog/macos-docker-setup/