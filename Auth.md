## `Auth::user()`

Get the currently authenticated user.

## `Auth::id()`

Get the ID for the currently authenticated user.

## `Auth::once(array $credentials = [])`

Log a user into the application without sessions or cookies.

## `Auth::onceusingId($id)`

Log the given user ID into the application without sessions or cookies.

## `Auth::validate(array $credentials = [])`

Validate a user's credentials.

## `Auth::basic($field = 'email', $extraconditions = [])`

Attempt to authenticate using HTTP Basic Auth.

## `Auth::onceBasic($field = 'email', $extraConditions = [])`

Perform a stateless HTTP Basic login attempt.

## `Auth::attemptBasic(Request $request, $field, $extraConditions = [])`

Attempt to authenticate using basic authentication.

## `Auth::attempt(array $credentials = [], $remember = false)`

Attempt to authenticate a user using the given credentials.

## `Auth::attemptWhen(array $credentials = [], $callbacks = null, $remember = false)`

Attempt to authenticate a user with credentials and additional callbacks.

## `Auth::loginusingId($id, $remember = false)`

Log the given user ID into the application.

## `Auth::login(AuthenticatableContract $user, $remember = false)`

Log a user into the application.

## `Auth::logout()`

Log the user out of the application.

## `Auth::logoutCurrentDevice()`

Log the user out of the application on their current device only.

## `Auth::logoutotherDevices($password, Sattribute = 'password')`

Invalidate other sessions for the current user.
