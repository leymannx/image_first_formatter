# Image First Formatter

Provides an "Image First" field formatter to display only the first image of
multi-value **image** fields.

1. [Download](https://github.com/leymannx/image_first_formatter/archive/8.x-1.x.zip)
1. Extract and rename folder `image_first_formatter`
1. Move module into `modules/custom`
1. Enable module
1. Flush cache   
1. Go to the display settings where you output your image field and select "Image First" formatter

To have this module added via composer paste the following into your
`composer.json` and then run `composer require leymannx/image_first_formatter`.

```json
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
            "version": "1.2",
            "type": "drupal-module",
            "source": {
                "url": "https://github.com/leymannx/image_first_formatter.git",
                "type": "git",
                "reference": "tags/8.x-1.2"
            }
        }
    },
    ...
```

### Refs

https://drupal.stackexchange.com/q/171466/15055
