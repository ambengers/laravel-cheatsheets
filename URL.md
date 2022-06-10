## `URL::full()`

Get the full URL for the current request.

## `URL::current()`

Get the current URL for the request.

## `URL::previous($fallback = false)`

Get the URL for the previous request.

## `URL::previousPath($fallback = false)`

Get the previous path info for the request.

## `URL::to($path, $extra = [], $secure = null)`

Generate an absolute URL to the given path.

## `URL::secure($path, $parameters = [])`

Generate a secure, absolute URL to the given path.

## `URL::asset($path, $secure = null)`

Generate the URL to an application asset.

## `URL::secureAsset($path)`

Generate the URL to a secure asset.

## `URL::assetFrom($root, $path, $secure = null)`

Generate the URL to an asset from a custom root domain such as CDN, etc.

## `URL::formatScheme($secure = null)`

Get the default scheme for a raw URL.

## `URL::signedRoute($name, $parameters = [1, $expiration = null, $absolute = true)`

Create a signed route URL for a named route.

## `URL::temporarySignedRoute($name, $expiration, $parameters = [], $absolute = true) `

Get the URL to a named route.

## `URL::route($name, $parameters = [], $absolute = true)`

Create a temporary signed route URL for a named route.

## `URL::toRoute($route, $parameters, $ absolute)`

Get the URL for a given route instance.

## `URL::action($action, $parameters = [], $ absolute = true)`

Get the URL to a controller action.
