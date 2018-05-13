# parcel-babelrc-rebuild-bug

This repo is a demo project for the `.babelrc` rebuild bug in parcel.

## Steps

1. Clone
2. `npm i`
3. `npm start`
4. Open http://localhost:45121 and observe the error in the console
5. Rename `.babelrc.example` to `.babelrc`
6. Kill and restart `npm start`
7. Refresh http://localhost:45121 and observe the error still exists
8. Kill parcel and `rm -rf .cache`
9. Restart `npm start` and observe the error has be resolved
