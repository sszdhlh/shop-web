# shop-web
It's a shop web dated from figma design and develope using React, Vue and Node.js/Next.js.
## Figma Link
https://www.figma.com/file/K5dDQ7MZNjtd16P2qAZkNE/Online-shipping-website-(Copy)?type=design&node-id=117%3A336&mode=design&t=j606FwFsp136BY22-1
## Frameworks
| Framework	| Description	| Version |
| ------------- | ------------- |------------- |
| Vue	| The library for web and native user interfaces	| 2.0x |
| Express | a web application framework for Node.js	|  |
|Axios | A simple promise based HTTP client for the browser and node.js	| 1.5.0 |
|webpack | an open-source JavaScript module bundler. |  |
|Node.js | an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside a web browser	|  |
|core-js | a modular standard library for JavaScript	| 3.8.3 |

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn dev
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```
### If have error
error:compile conflict with essorts emit to the same filename index.html
Reason: Vue version is not 2.0x
Solution: Update the Vue version from 3.0x even 4.0x to the 2.0x, using cmd commond as below:
```
#Downgrade the Vue version to 2.x
1. Install Vue 2.0x
yarn remove vue
yarn add vue@2
#or use npm:
npm uninstall vue
npm install vue@2

```
```
#Downgrade the version of vue-template-compiler
yarn remove vue-template-compiler
yarn add vue-template-compiler@2

```
```
#Downgrade or change other related libraries
yarn remove vue-router
yarn add vue-router@3
#or use npm:
npm uninstall vue-template-compiler
npm install vue-template-compiler@2


```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
