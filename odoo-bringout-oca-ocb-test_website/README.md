# Website Test

This module contains tests related to website. Those are
present in a separate module as we are testing module install/uninstall/upgrade
and we don't want to reload the website module every time, including it's possible
dependencies. Neither we want to add in website module some routes, views and
models which only purpose is to run tests.

## Installation

```bash
pip install odoo-bringout-oca-ocb-test_website
```

## Dependencies

- web_unsplash
- website
- theme_default

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 17.0
- Path: addons/test_website

## License

This package preserves the original LGPL-3 license.
