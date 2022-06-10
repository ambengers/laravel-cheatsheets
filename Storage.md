## `Storage::get($path)`

Get the contents of a file.

## `Storage::download($path, $name = null, array $headers = [])`

Create a streamed download response for a given file.

## `Storage::put($path, $contents, $options = [])`

Write the contents of a file.

## `Storage::putFile($path, $file, $options = 0)`

Store the uploaded file on the disk.

## `Storage::putFileAs($path, $file, $name, $options = [])`

Store the uploaded file on the disk with a given name.

## `Storage::getVisibility($path)`

Get the visibility for the given path.

## `Storage::setVisibility($path, $visibility)`

Set the visibility for the given path.

## `Storage::prepend($path, $data, $separator = PHP_EOL)`

Prepend to a file.

## `Storage:: append($path, $data, $separator = PHP_EOL)`

Append to a file.

## `Storage::delete($paths)`

Delete the file at a given path.

## `Storage::copy($from, Sto)`

Copy a file to a new location.

## `Storage::move($from, $to)`

Move a file to a new location.

## `Storage::size($path)`

Get the file size of a given file.

## `Storage::mimeType($path)`

Get the mime-type of a given file.

## `Storage::lastModified($path)`

Get the file's last modification time.

## `Storage::files($directory = null, $recursive = false)`

Get an array of all files in a directory.
