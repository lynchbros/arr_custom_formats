# Custom Formats for Radarr and Sonarr

## Description

This repo contains the custom formats and configs for our Recyclarr implementation.

## Usage

1. In top level of ``recyclarr's`` app folder, create a new file named ``settings.yml``

2. Add the below in order to import this library

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/recyclarr/recyclarr/master/schemas/settings-schema.json

resource_providers:
  - name: arr_custom_formats
    type: trash-guides
    clone_url: https://github.com/lynchbros/arr_custom_formats.git
    reference: main
```