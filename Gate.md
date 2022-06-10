## `Gate::has ($ability)`

Determine if a given ability has been defined.

## `Gate::allowIf ($condition, $message = null, $code = null)`

Perform an on-demand authorization check.

## `Gate::denyIf ($condition, $message = null, $code = null)`

Perform an on-demand authorization check.

## `Gate::define($ability, $callback)`

Define a new ability.

## `Gate::resource ($name, $class, array $abilities = null)`

Define abilities for a resource.

## `Gate::policy($class, $policy)`

Define a policy class for a given class type.

## `Gate::before(callable $callback)`

Register a callback to run before all Gate checks.

## `Gate::after(callable $callback)`

Register a callback to run after all Gate checks.

## `Gate::allows($ability, $arguments = [])`

Determine if the given ability should be granted for the current user.

## `Gate::denies($ability, $arguments = [])`

Determine if the given ability should be denied for the current user.

## `Gate::check($abilities, $arguments = [])`

Determine if all of the given abilities should be granted for the current

## `Gate:: authorize( $ability, $arguments = [])`

Determine if the given ability should be granted for the current user.

## `Gate::inspect($ability, $arguments = [])`

Inspect the user for the given ability.

## `Gate::parameterAllowsGuests($parameter)`

Determine if the given parameter allows guests.
