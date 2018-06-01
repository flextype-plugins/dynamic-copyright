# Copyright Plugin for [Flextype](http://flextype.org/)
![version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg?style=flat-square)
![Flextype](https://img.shields.io/badge/Flextype-0.x-green.svg?style=flat-square)
![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)

GitHub Gist plugin will embed a GitHub Gist into the page.

## Installation
1. Unzip plugin to the folder `/site/plugins/`
2. Go to `/site/config/site.yaml` and add plugin name to plugins section.
3. Save your changes.

Example:
```
plugins:
  - copyright
```

## Usage in page content

```
[copyright]
```

## Usage in the template

Define Flextype namespace in the template if it is not defined yet.
```
<?php namespace Flextype; ?>
```

Display copyright
```
<?php echo copyright(); ?>
```


## Settings

```yaml
enabled: true # or `false` to disable the plugin
copyright: "Copyright &copy; {year}" # Copyright information
```

## License
See [LICENSE](https://github.com/flextype-plugins/copyright/blob/master/LICENSE)
