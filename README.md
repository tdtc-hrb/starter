# starter
A very basic (sample only) starter for playing with Redux
[fork](https://github.com/redux-book/starter)

## changelog
- Change the default port to 8181

package.json:
```xml
"start": "webpack-dev-server --hot --progress --port 8181"
```

- mode    
fixed WARNING in configuration:
The 'mode' option has not been set, webpack will fallback to 'production' for this value. Set 'mode' option to 'development' or 'production' to enable defaults for each environment.
You can also set it to 'none' to disable any default behavior. Learn more: https://webpack.js.org/concepts/mode/

webpack.config.js:
```js
mode: 'development',
```

- cli    
must be install webpack-cli

package.json:
```
"webpack-cli": "^4.9.1"
```

### v5 change
> webpack v5.x

move "index.html" to "public/index.html"


## run
```bash
git clone https://github.com/tdtc-hrb/starter.git
cd starter  
npm install  
npm start  
```
