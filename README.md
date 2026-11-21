> **This CLI has been replaced.** Its dev commands (`beam dev`, `beam ui`, `beam api`, `beam db`, `beam kill`) moved to [`bin/beam`](https://github.com/beamlynx/beamlynx-desktop/blob/main/bin/beam) in [beamlynx/beamlynx-desktop](https://github.com/beamlynx/beamlynx-desktop).
>
> **Why:** since November 2026, Pine, the Beamlynx interface and the desktop app are one repo. The CLI only existed to run those separate repos side by side, through a config file of paths. Inside one repo, `bin/beam` finds everything itself.
>
> This repo is archived and read-only. To use Beamlynx, get the app from [beamlynx.com](https://beamlynx.com).

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
