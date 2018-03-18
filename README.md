# Image First Formatter

Provides an "Image First" field formatter to display only the first image of multi-value **image** fields.

1. [Download](https://github.com/leymannx/image_first_formatter/archive/8.x-1.x.zip)
2. Extract and rename folder `image_first_formatter`
3. Move module into `modules/custom`
4. Enable module
5. Use formatter

![Screenshot](https://leymannx.de/image_first_formatter.png "Drupal Image First Formatter")

To have this module added via composer paste the following into your `composer.json` and then run `composer require leymannx/image_first_formatter`.
```
...
"repositories": [
    {
        "type": "composer",
        "url": "https://packages.drupal.org/8"
    },
    {
        "type": "package",
        "package": {
            "name": "leymannx/image_first_formatter",
            "version": "1.1",
            "type": "drupal-module",
            "source": {
                "url": "https://github.com/leymannx/image_first_formatter.git",
                "type": "git",
                "reference": "tags/8.x-1.1"
            }
        }
    },
    ...
```

### Refs

https://drupal.stackexchange.com/q/171466/15055
