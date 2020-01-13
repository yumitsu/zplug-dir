zplug-dir - get path of installed package
-----------------------------------------

### Why?
At some point I needed a helper for `zplug` to obtain locations of installed packages, without direct interaction with fs if possible.

### Installation
##### With `zplug`:
Add to your `$ZPLUG_LOAD_FILE`:
```
zplug "yumitsu/zplug-dir", \
  from:github, \
  as:command, \
  use:'bin/zplug-dir'
```

### Usage
```shell
$ zplug dir b4b4r07/enhancd
/usr/local/opt/zplug/repos/b4b4r07/enhancd # <--- Installed package path
```

### Caveats
Unknown for present time.

### Credits
Author: [@yumitsu](https://github.com/yumitsu) on behalf of Forgotten Labors Initiative.

### License

MIT License

Copyright (c) 2020 Forgotten Labors Initiative.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
