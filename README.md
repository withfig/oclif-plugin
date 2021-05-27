fig-oclif-plugin
================

Export a Fig completion spec generated using the oclif internal representation.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)

# Setup

1. Add the [@oclif/plugins-plugin](https://github.com/oclif/plugin-plugins). (This is only necessary for developement and does not need to be included in production).
> First add the plugin to your project with `yarn add @oclif/plugin-plugins`, then add it to the package.json of the oclif CLI:
>
> ```json
> {
>  "name": "mycli",
>  "version": "0.0.0",
>  "oclif": {
>    "plugins": ["@oclif/plugin-help", "@oclif/plugin-plugins"]
>  }
> }
> ```

2. Clone this repo and then inside of it run `your-cli-name plugins:link`. This will add the `fig-completion` command to `your-cli-name`.

3. Run `your-cli-name fig-completion -o output-file-name`. (The correct file extension will be added automatically)


