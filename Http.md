## `Http::baseUrl(string $url)`

Set the base URL for the pending request.

## `Http::withBody($content, $contentType)`

Attach a raw body to the request.

## `Http::asJson()`

Indicate the request contains JSON.

## `Http:: asForm()`

Indicate the request contains form parameters.

## `Http::attach($name, $contents = '', $filename = null, $headers = [])`

Attach a file to the request

## `Http:: asMultipart()`

Indicate the request is a multi-part form request.

## `Http::acceptJson()`

Indicate that JSON should be returned by the server.

## `Http::withHeaders(array headers)`

Add the given headers to the request.

## `Http::withBasicAuth(string $username, string $password)`

Specify the basic authentication username and password for the request.

## `Http::withDigestAuth($username, $password)`

Specify the digest authentication username and password for the request.

## `Http::withToken($token, $type = 'Bearer')`

Specify an authorization token for the request.

## `Http::withuserAgent($userAgent)`

Specify the user agent for the request.

## `Http::withCookies(array $cookies, string $domain)`

Specify the cookies that should be included with the request.

## `Http::dd()`

Dump the request before sending and end the script.
