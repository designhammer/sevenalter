# Seven Alter - Theme

Seven Alter is an admin theme for Drupal based on Seven admin theme.

<img src="screenshot.png" width="335" height="250">

Also checkout the [**Seven Alter Toolbar**](https://github.com/designhammer/sevenalter_toolbar) module. This module is used to display the toolbar theme on user-facing pages.


## Add to a Drupal site

[Drupal.org doc: Managing dependencies for a custom project](https://www.drupal.org/docs/develop/using-composer/managing-dependencies-for-a-custom-project)

Add to composer.json (the first part is already there).

    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.drupal.org/8"
        },
        {
            "type": "git",
            "url": "https://github.com/designhammer/sevenalter.git"
        }
    ],

Require the modules.

    composer require designhammer/sevenalter


## CSS Overrides

Before enabling this theme, please duplicate this file `css/example.override-styles.css` and rename it `css/sevenalter-overrides.css`.
⚠️ Failing to create this file will cause a console error.
