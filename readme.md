# tistorekit

  Titanium Storekit Module -  For in app purchases

```
$ git clone https://github.com/euforic/TiStorekit.git
$ cd TiStorekit
$ cp tistorekit-iphone-0.1.zip /Library/Application Support/Titanium/
```
Register your module with your application by editing `tiapp.xml` and adding your module.
```
<modules>
  <module version="0.1">tistorekit</module>
</modules>
```
Require you module in whatever js file you plan to use it in
```
var my_module = require('tistorekit');
```
## Usage

see `example/app.js` and example `example/storekit.js`

## License

(The MIT License)

Copyright (c) 2012 Christian Sullivan &lt;cs@euforic.co&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.