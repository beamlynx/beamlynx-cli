> **This CLI is no longer maintained, and this repo is archived.** Beamlynx is now one repo, [beamlynx/beamlynx-desktop](https://github.com/beamlynx/beamlynx-desktop). Get the app from [beamlynx.com](https://beamlynx.com).

# Pine CLI

Run the server:

```
pine run serve
```

or with a specific configuration:

```
CONFIG=default pine run serve
```

or use encrypted configuration:

```
CONFIG=prod.nc pine run serve
```

# Dev Setup

Clone with submodules:

```
git clone --recurse-submodules git@github.com:pine-lang/pine-cli.git
```

One time setup:

- Install dependencies `cd pine-app && npm install`

```
pine run dev-server
pine run app
```

## License

[PolyForm Noncommercial License 1.0.0](LICENSE) - free for noncommercial use. For commercial licensing, contact contact@grephyte.com.
