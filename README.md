## Overview

Marketplace has dependencies on multiple technologies.

* [Ganache](https://trufflesuite.com/ganache/) - private Blockchain, to run application localy

## To run the app
1. run `npm install` to install dependencies

2. Then migrate a contract to Ganache, contract can be found in the `contracts` folder. It's called `CourseMarketplace.sol`

* To migrate the contract run `truffle migrate` in the terminal while Ganache network is setup and running.

* Do not forget to link `trufle-config.js` with Ganache, just go to `config` and click `Add Project`

* `keys.json` must be created if you want to deploy to Ropsten, if not, just remove import of `keys.json` from `trufle-config.js` and also comment out `ropsten` configuration

3. Now everything is setup and you can test out the app.

* Run `npm run dev` in the terminal. App will run at `localhost:3000`

![methodology](https://github.com/Allanrodriques/DLP-Final-Year/assets/68966594/9dfac61e-1d9b-4928-a454-2d6c04b884d2)
![login](https://github.com/Allanrodriques/DLP-Final-Year/assets/68966594/ec139408-a5d4-40a3-9ee9-480ea243d1c1)
![marketplace](https://github.com/Allanrodriques/DLP-Final-Year/assets/68966594/f56e585a-8602-4b9f-96bb-71f6b4d22aea)
![mycourses](https://github.com/Allanrodriques/DLP-Final-Year/assets/68966594/8fca1737-f7cd-4d83-8537-21538683dded)
![report](https://github.com/Allanrodriques/DLP-Final-Year/assets/68966594/3560a63f-1988-4c54-b887-345976658035)
