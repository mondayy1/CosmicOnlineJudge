# OnlineJudge Front End

>### A multiple pages app built for OnlineJudge.
>[Link]: 203.255.81.70:8026

## Members
+ TODO

## Features

+ TODO: Edit English to Korean (Problem, Contest etc...)
+ TODO: FE -> Docker Image file
+ Backend uses Docker Version of Qingdao University's Online Judge Server module.
+ Being used as an algorithm site exclusively for COSMIC.

## Get Started

Install nodejs **v8.12.0** first.

### Linux

```bash
npm install
# we use webpack DllReference to decrease the build time,
# this command only needs execute once unless you upgrade the package in build/webpack.dll.conf.js
export NODE_ENV=development 
npm run build:dll

# the dev-server will set proxy table to your backend
export TARGET=http://Your-backend

# serve with hot reload at localhost:8080
npm run dev
```

## Screenshots

TODO

## Browser Support

Modern browsers and Internet Explorer 10+.


## LICENSE

[MIT](http://opensource.org/licenses/MIT)
