# atoll-theme-editorial

Official **editorial** theme for `atoll-cms`.

## Install

```bash
php bin/atoll theme:install https://github.com/atoll-cms/atoll-theme-editorial/archive/refs/heads/main.zip
php bin/atoll theme:activate editorial
```

## Scope

- `assets/main.css` contains the visual style.
- `templates/layouts/base.twig` and `templates/components/*` override the shared base layout structure.
- Page templates can remain minimal and still use core fallbacks where appropriate.
