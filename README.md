# WEB_MS

This project is running on Angular version 7.2.12 with latest version of Node.

clone project
To clone project in your system  use command in your terminal git clone https://github.com/AntaraShah/web_ms.git
Once cloned, execute npm i. There might be some issue with node-sass module.
Solution for node-sass


Remove node-sass from package.json.
Delete node-modules

Run npm i

Once done, run npm i node-sass@4.12.0 (Refer node-sass version as per your node version)
Revert changes in package.json.

Always delete package-lock.json file from project to avoid issue with installation.


Development server
To run modules: ng serve and navigate to http://localhost:4200/.
