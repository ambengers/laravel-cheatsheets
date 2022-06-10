## `Cache::pull($key, $default = null)`

Retrieve an item from the cache and delete it.

## `Cache::put($key, $value, $ttl = null)`

Store an item in the cache.

## `Cache::add ($key, $value, $ttl = null)`

Store an item in the cache if the key does not exist.

## `Cache::increment ($key, $value = 1)`

Increment the value of an item in the cache.

## `Cache::decrement ($key, $value = 1)`

Decrement the value of an item in the cache.

## `Cache::forever ($key, $value)`

Store an item in the cache indefinitely.

## `Cache::remember ($key, $tti, Closure $callback)`

Get an item from the cache, or execute the given Closure and store the result.

## `Cache::sear($key, closure $callback)`

Get an item from the cache, or execute the given Closure and store the result forever.

## `Cache:: rememberForever ($key, Closure $callback)`

Get an item from the cache, or execute the given Closure and store the result forever.

## `Cache::forget ($key)`

Remove an item from the cache.

## `Cache::getStore()`

Get the cache store implementation. '
