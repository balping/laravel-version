## Moved to GitLab

**Warning**: This project has been moved to GitLab: https://gitlab.com/balping/laravel-version

----

# Laravel Version

Simple wrapper around `version_compare` to check Laravel versions.

## Install

```bash
composer require balping/laravel-version
```

## Example

```php
if (LaravelVersion::min('5.5')) {
	// do something
} else {
	// do something else
}
```

## License

This package is licensed under the Expat (MIT) license.