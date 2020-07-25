# pagespeed.waleed.de
After you make a fast web site, keep it fast by measuring it over time. 

* Requires Node 12+
* Each file in `_data/sites/*.js` is a category and contains a list of sites for comparison.

## Run locally

_After cloning you’ll probably want to delete the initial `_data/sites/*.js` files and create your own file with a list of your own site URLs!_

```
npm install
npm run test-pages
npm run start
```