# ci-workflow

# Node.js

[![NPM](https://nodei.co/npm/express.png?downloads=true&stars=true)](https://www.npmjs.com/package/express)    
`$ npm init`  
`$ npm install express --save`  

`$ node index.js`  
 package.json
 >"scripts": {
    "start": "node index.js"
  }

`$ npm start`  

[![NPM](https://nodei.co/npm/mocha.png?downloads=true&stars=true)](https://www.npmjs.com/package/mocha)   
$ npm install mocha --save-dev
 package.json
 >"scripts": {
  "test": "mocha test"
}  

`$ npm test`  


# GitHub

`$ git init .`  
`$ git status`  

.gitignore
>config.js  
node_modules/

`$ git push -u origin master`  
https://github.com/USER_NAME/ci-workflow


# [CircleCI](https://circleci.com/)
`Add Projects` → `Build project`

# QA
> bash: line 1: grunt: command not found grunt build-dev returned exit code 127

[npm install returned exit code 127](https://discuss.circleci.com/t/successful-build-is-now-failing-when-trying-to-rebuild-it/810)

# References
* https://github.com/amowu/hello-ci-workflow
