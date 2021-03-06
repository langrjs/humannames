# HumanNames
A list, huge one (~200K) of human male/female first/last names.

## Installation and Usage

```
npm i --save humannames
```

```javascript
const names = require("humannames");
console.log(names) // WARNING: this will print out the whole object
console.log(names["Lui"]) // 1
console.log(names["not a name"]) // undefined
```

### What's included

* Male names
* Female names
* First names
* Last names
* English + common non-english names
* Two formats JSON and line-break-delimited plain text file.

### Data Source
Scrapping social media websites + governmental censuses.

## License

The MIT License (MIT)

Copyright (c) 2017 Alex Corvi

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