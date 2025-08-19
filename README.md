# minecraft-assets

Provide minecraft 1.8.8, 1.9, 1.10, 1.11.2, 1.12, 1.13, 1.13.2, 1.14.4, 1.15.2, 1.16.1, 1.16.4, 1.17.1, 1.18.1, 1.19.1, 1.20.2, 1.21.1, 1.21.4, 1.21.5, 1.21.6, 1.21.7 and 1.21.8 assets along with json files that help to use them.

Generated using [image_names.js](https://github.com/PrismarineJS/minecraft-jar-extractor/blob/master/image_names.js)

## Automated Updates

This repository supports automated updates via workflow dispatch. When a new Minecraft version is released, the assets can be automatically generated and a pull request created by triggering the `handle-mcdata-update` workflow with the new version number.

## Wrappers

Minecraft-assets is language independent, you can use it with these language specific modules :

| Wrapper name | Language |
| --- | --- |
| [node-minecraft-assets](https://github.com/rom1504/node-minecraft-assets) | Node.js |

## Data in `common/`

| File name | Description |
| --- | --- |
| `pre_flattening_texturepack_mappings` | Data used by minecraft to decide which texture to use from an item name and legacy metadata as a number |
| `legacy_texturepack_mappings.json` | Data used by minecraft to convert old resourcepacks to use the new item naming |
