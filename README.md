# Typescript Module Demo

## How to get it working 

 - Clone repository
 - Run `npm install` in both directories i.e `testModule` and `moduleConsumer`.
 
 _Note: While resolving the `testModule` dependencies use the `--ignore-scripts` flag as the `preinstall` script gets run by default on executing `npm install`_.
 - Inside the `moduleConsumer` directory run the command `npm install ../testModule`.
 - Run `moduleConsumer` using `npm start`.