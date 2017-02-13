## Angular Component Router Tutorial Demo

_This demo illustrates Angular 2 Routers.
Originally derived from an example by scotch_

**note: The package.json is very specific. Do not upgrade or modify (at your own risk if you do). If you are going to upgrade, create a separate branch.**

KNOWN ISSUES:
* Upgrading Typings causes duplicate variable error issues. Fix in progress. see http://stackoverflow.com/questions/31322525/typescript-confusing-duplicate-identifier-error-message

* Upgrading Angular to latest 2.4.7 (as of Feb 2017) or using latest Angular CLI causes issues with JSONP and http module. Fix in progress. See http://stackoverflow.com/questions/42053160/uncaught-referenceerror-ng-jsonp-req0-finished-is-not-defined-at

This example uses RxJS and observables, which will likely be incorporated into ES6 / Angular later in 2017. see http://blog.angular-university.io/functional-reactive-programming-for-angular-2-developers-rxjs-and-observables/ for info.

To run, clone the demo and run:

```bash
# Install dependncies
npm install
# Start app
npm start
```
