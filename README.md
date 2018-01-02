# drupal-packagist

Provides a Packagist based repository to allow Drupal 7 modules and themes to be included in your site via composer. Inspired
by the [Haehnchen/drupal-packagist](https://github.com/Haehnchen/drupal-packagist) project.

## Usage

Add this project as a repository in your `composer.json`:
```
"repositories": [
    {
        "type": "composer",
        "packagist": "false",
        "url": "https://raw.githubusercontent.com/sprak3000/drupal-packagist/master/packages-7.x.json"
    }
]
```

And then add your requirements in the form of `"sprak3000-drupal/<module | theme>": "<version>"`:
```
"require": {
    "sprak3000-drupal/date": "7.2.8",
    "sprak3000-drupal/bueditor": "7.1.0-dev",
    "sprak3000-drupal/entity_view_mode": "7.1.0-rc1",
    "sprak3000-drupal/filefield_paths": "7.1.0-beta4"
}
```

For an example of it in use, see the [composer.json file for the drupal-composed project](https://github.com/sprak3000/drupal-composed/blob/master/composer.json).

## Contributing

[Drupal 8](https://www.drupal.org/8) has been released. This repository is being archived and left as reference material. It will no longer be updated, and no contributions are being accepted at this time. 

~~Are we missing a module or theme in the list? A particular version? Pull requests are encouraged to build this repo out!~~
