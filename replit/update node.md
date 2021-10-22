Run in shell
```shell
npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH
```
- - -
then you will create a file called `.replit` to which you will put the following content
```js
run = "node_modules/.bin/node index.js"
```
once done, Yay!! you have already updated `node.js` in replit
