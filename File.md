## `File::exists($path)`

Determine if a file or directory exists.

## `File::missing ($path)`

Determine if a file or directory is missing.

## `File::get($path, $lock = false)`

Get the contents of a file.

## `File::sharedGet($path)`

Get contents of a file with shared access.

## `File::getRequire($path, array $data = [])`

Get the returned value of a file.

## `File::requireOnce ($path, array $data = [])`

Require the given file once.

## `File::lines ($path)`

Get the contents of a file one line at a time.

## `File::hash ($path)`

Get the MD5 hash of the file at the given path.

## `File::put($path, $contents, $lock = false)`

Write the contents of a file.

## `File::replace($path, $content)`

Write the contents of a file, replacing it atomically if it already exists.

## `File::replaceInFile($search, $replace, $path)`

Replace a given string within a given file.

## `File::prepend($path, $data)`

Prepend to a file.

## `File::append($path, $data)`

Append to a file.

## `File::chmod($path, $mode = null)`

Get or set UNIX mode of a file or directory.
