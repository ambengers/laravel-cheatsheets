## `Redirect::home()`

Create a new redirect response to the "home" route.

## `Redirect::back($status = 302, $headers = [], $fallback = false)`

Create a new redirect response to the previous location.

## `Redirect::refresh($status = 302, $headers = [])`

Create a new redirect response to the current URI.

## `Redirect::guest($path, $status = 302, $headers = [], $secure = null)`

Create a new redirect response, while putting the current URL in the session.

## `Redirect::intended($default = '/', $status = 302, $headers = U, $secure = null)`

Create a new redirect response to the previously intended location.

## `Redirect::setIntendedurl($url)`

Set the intended url.

## `Redirect::to($path, $status = 302, $headers = [], $secure = null)`

Create a new redirect response to the given path.

## `Redirect:: away($path, $status = 302, $headers = [])`

Create a new redirect response to an external URL(no validation).

## `Redirect::secure($path, $status = 302, $headers = [])`

Create a new redirect response to the given HTTPS path.

## `Redirect::route($route, $parameters = [], $status = 302, $headers = [])`

Create a new redirect response to a named route.

## `Redirect::action($action, $parameters = [], $status = 302, $headers = [])`

Create a new redirect response to a controller action.

## `Redirect::getUrlGenerator()`

Get the URL generator instance.

## `Redirect::setSession(SessionStore $session)`

Set the active session store.
