## `Lang::hasForLocale($key, $locale = null)`

Determine if a translation exists for a given locale.

## `Lang::has($key, $locale = null, $fallback = true)`

Determine if a translation exists.

## `Lang::get($key, array $replace = [], $locale = null, $feedback = true)`

Get the translation for the given key.

## `Lang::choice($key, $number, array $replace = [], $locale = null)`

Get a translation according to an integer value.

## `Lang::addLines(array $lines, $locale, $namespace = '*')`

Add translation lines to a given locale.

## `Lang::load($namespace, $group, $locale)`

Load the specified language group.

## `Lang::addNamespace($namespace, $hint)`

Add a new namespace to the loader.

## `Lang::addJsonPath($path)`

Add a new JSON path to the loader.

## `Lang::parseKey($key)`

Parse a key into namespace, group and item.

## `Lang::determineLocalesUsing($callback)`

Specify a callback that should be invoked to determine the locale.

## `Lang::getSelector()`

Get the message selector instance.

## `Lang::setSelector(MessageSelector $selector)`

Set the message selector instance.

## `Lang::getLoader()`

Get the language line loader implementation.

## `Lang::locale()`

Get the default locale being used.
