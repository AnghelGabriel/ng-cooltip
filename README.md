# ng-cooltip

An angular module with a small collection of various hover tooltip. This module is an angular wrapper of [Tooltip Styles Inspiration](https://github.com/codrops/TooltipStylesInspiration).

## Usage:

1. Install ng-cooltip from bower or import script manually
  ```
    $ bower install ng-cooltip --save
  ```
  
2. Include the supplied JS file

    ```html
    <script type='text/javascript' src='dist/ng-cooltip.min.js'></script>
    ```
    
3. Include the supplied CSS file (or create your own CSS to override defaults)

    ```html
    <link rel='stylesheet' href='dist/ng-cooltip.min.css' type='text/css' />
    ```
    
4. Add ng-tooltip dependency to your app

    ```js
    angular.module('myApp', ['ng-cooltip'])
    ```
#### Directives

* cooltip-classic
* cooltip-box
* cooltip-round

| option          | Description                                    | Values                |
| -------------   |:----------------------------------------------:| ---------------------:|
| cooltip-item    | word / sentence that fires the tooltip         | String                |
| cooltip-content | content on tooltip, it could be an html element| String / html element |
| cooltip-effect  | firing tooltip effect                          | [1-5]                 |

Usage example:

```html
<p>Lorem ipsum dolor sit amet, et perfecto deserunt <cooltip-classic cooltip-item="intellegam" cooltip-content="Vel ut solum erant dicit, eum te aperiam efficiendi, et eos alia eruditi persecuti. Ius ex omnis voluptatum" cooltip-effect="1"></cooltip-classic>nam, quem doming platonem vim no.</p>
```
## Copyright and license

```
The MIT License

Copyright (c) 2012 – 2015 Olivier Louvignes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
