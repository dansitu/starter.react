# starter.react
An extremely basic app skeleton for Express and React, using NPM as the only build tool.

#### 1. Build tools suck
You have limited time and energy to create excellent software.
<br/>
**Gulp, Grunt and friends sound exciting, but take more work to configure than they save you.**

#### 2. Bower sucks
You already have great dependency management.
<br/>
**Bower may be purpose-built, but it's unnecessary when NPM works perfectly for front-end code.**

#### 3. Simplicity rules
Your code should be easy to run.
<br/>
**Complex, custom build systems will take new team member weeks to understand.**

## How to use

1. Run `npm install` to install all the dependencies
1. Run `npm run build:js` to build the React code in `client/src` with Browserify and Babel. It outputs to `client/build/bundle.js`.
1. Run `npm run watch` to do this automatically on every file change.
