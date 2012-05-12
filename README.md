RESTtest
========

This is just a small app that executes a REST call (GET) and show the result in the TextView.
Nothing pretty about it. Enter the URL in the EditText box and press the button.
App checks that a network is available and then executes if that is the case.
The REST call happens in a AsyncTask to avoid locking of the UI thread.

This code is based on this great StackOverflow post:
http://stackoverflow.com/a/3506039

Better would be using a Service or Content Provider
https://www.youtube.com/watch?v=xHXn3Kg2IQE

http://stackoverflow.com/questions/4948152/need-sample-android-rest-client-project-which-implements-virgil-dobjanschi-rest


#License
This software is available under the [MIT licence](http://www.opensource.org/licenses/mit-license.php)

**Copyright (c) 2012 -- Armin Krauss**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

