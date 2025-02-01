# @GiganticMinecraft/renovate-config

Renovate Config for use with GiganticMinecraft.

## Usage

Renovate configuration file as follows:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>GiganticMinecraft/renovate-config"]
}
```

Specify the preset as follows:

```json
{
  "extends": ["github>GiganticMinecraft/renovate-config//presets/plugin"]
}
```

When overriding the preset settings, simply add the configuration below it.

## Configuration variations

This Renovate Config is based on the [common settings (`presets/base.json`)](./presets/base.json) and can be adjusted according to your needs.

It is recommended to use the [default settings](#usage) unless there is a specific reason not to.

### `plugins`

```json
{
  "extends": ["github>GiganticMinecraft/renovate-config//presets/plugin"]
}
```

This is a configuration for plugins developed in GiganticMinecraft.

## License

This configuration is published under the [MIT license](./LICENSE).
