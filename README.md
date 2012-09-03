# zf2-assetwig

v1.0.1

This module integrates [Assetic](https://github.com/kriswallsmith/assetic) and [Twig](http://twig.sensiolabs.org/) to a ZF2 appliation.

# Installation

Use composer. `"minimum-stability": "dev"` is required because `twig/extensions` is still in development stage.

```json
{
    "minimum-stability": "dev",
    "require": {
        "heartsentwined/zf2-assetwig": "1.0.*"
    }
}
```

Then add `Assetwig` to the `modules` key in `(app root)/config/application.config.yml`

# Config

Copy `config/assetwig.local.php.dist` to `(app root)/config/autoload/assetwig.local.php`, and modify the settings. Instructions included in config file.
