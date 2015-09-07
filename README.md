# NGBLPT
An Angular boilerplate that includes:
- [gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache)
- [gulp-autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer)
- [gulp-babel](https://github.com/babel/gulp-babel)
- [gulp-ng-annotate](https://github.com/Kagami/gulp-ng-annotate)
- [karma](https://github.com/karma-runner/karma)
- [karma-mocha](https://github.com/karma-runner/karma-mocha)
- [karma-chai](https://github.com/xdissent/karma-chai)
- [main-bower-files](https://github.com/ck86/main-bower-files)

Far from perfect, but a decent starting point.

## Getting started
1. `npm install` installs packages (and bower components on postinstall)
2. `npm start` begins watching and compiling with gulp
3. `npm run test` starts karma and begins watching `*.spec.js`

Local binaries for Gulp and Karma are used to avoid global installs. Yay!
