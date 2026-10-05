<!-- tyhp-readme:start -->
# tyhpdef/spatie-flare-client-php

Tyhp type definitions for `spatie/flare-client-php` `2.10.2`.

```bash
composer require --dev tyhpdef/spatie-flare-client-php:2.10.2
```

This is a metapackage. Composer also installs `tyhpdef/spatie-flare-client-php-impl` (type files).
Require **this** name, not `tyhpdef/spatie-flare-client-php-impl`.

See https://tyhplang.com.

## Maintain `spatie/flare-client-php`? Ship the types yourself

If you are a Packagist maintainer of `spatie/flare-client-php`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/spatie-flare-client-php-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `spatie/flare-client-php` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/spatie-flare-client-php": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `spatie/flare-client-php` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `spatie/flare-client-php` with a real constraint,
   `"replace": { "tyhpdef/spatie-flare-client-php": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `spatie/flare-client-php` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/spatie-flare-client-php` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
