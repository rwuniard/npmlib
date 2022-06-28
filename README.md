# Creating an NPM library (rwtestlib)

First you need to register an account at the npm registry (npmjs.com)

After creating the nodejs math simple module that just have add and multiply functions.

To push the library to the npm registry:
- npm login
- npm publish

To pull the library in your project
- npm install rwtestlib
- put this require section in your code
  - const math = require('rwtestlib')
  - Start using it in your code. Example: math.add(2,3) 

