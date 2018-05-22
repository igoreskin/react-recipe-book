React Recipe Book

React with Redux Middleware

This is a simple CRUD React application where you can create, read, update and delete cooking recipes. Async actions are used to send data to and receive data from an external API. Redux middleware is used to respond to and modify the state change.

Installation instructions

In the subfolder recipe-book-api run rake db:migrate, rake db:seed to seed the database. Then run rails s –p 3001 to launch the Rails server.
In another terminal window, in the subfolder recipe-book-client run nmp install && nmp start, the landing page will then pop up the browser.

Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/igoreskin/react-recipe-book . This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the Contributor Covenant code of conduct.

License

Copyright (c) 2018 Igor Eskin

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
