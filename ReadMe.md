# ExpressWebJs Elucidate Preset

This is the base config files **(recommended by the core team)** to be extended to your ExpressWebJs typescript projects.

## Usage

Install the package from npm registry as follows

```sh
npm i -D @elucidate/preset

# yarn
yarn add -D @elucidate/preset
```

and then setup your config file to extend the base config

**tsconfig.json**

```json
{
  "extends": "./node_modules/elucidate_preset/tsconfig",
  "compilerOptions": {
    "paths": {
      "App/*": ["./App/*"],
      "Config/*": ["./Config/*"],
      "Database/*": ["./Database/*"],
      "Routes/*": ["Routes/*"]
    }
  }
}
```
