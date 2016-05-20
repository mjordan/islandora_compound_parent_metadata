# Islandora Compound Parent Metadata

## Introduction

Simple utility module that adds the parent's metadata below an object if that object is a child of compound object. Works with default Dublin Core metadata displays as well as metadata displays managed by Islandora Solr Metadata. In the latter case, uses the metadata display configuration associated with the parent object.

![Parent metadata without being expanded](https://dl.dropboxusercontent.com/u/1015702/linked_to/ISLANDORA-1718/ISLANDORA-1718-1.png)
![Parent metadata expanded](https://dl.dropboxusercontent.com/u/1015702/linked_to/ISLANDORA-1718/ISLANDORA-1718-3.png)

## Requirements

* [Compound Object Solution Pack](https://github.com/Islandora/islandora_solution_pack_compound)

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

There is only one admin setting, the label to use for the parent's metadata. To set it, go to Administration > Islandora > Islandora Utility Modules > Islandora Display Parent Metadata.

## Maintainer

* [Mark Jordan](https://github.com/mjordan)

## Development and feedback

Pull requests are welcome, as are use cases and suggestions.

## License

* [GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
