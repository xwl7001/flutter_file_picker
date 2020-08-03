# file_picker

This Go package implements the host-side of the Flutter [file_picker](https://github.com/miguelpruivo/flutter_file_picker) plugin.

## Usage

Modify your applications `options.go`:

```
package main

import (
	... other imports ....
	file_picker "github.com/xwl7001/flutter_file_picker"
)

var options = []flutter.Option{
	... other plugins and options ...

	flutter.AddPlugin(&file_picker.FilePickerPlugin{}),
}
```
