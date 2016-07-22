# ui5_host
## Project Description

[![Join the chat at https://gitter.im/RichardMartens/ui5_host](https://badges.gitter.im/RichardMartens/ui5_host.svg)](https://gitter.im/RichardMartens/ui5_host?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
This is an application for hosting of openui5 apps. It includes an nodejs http server, so you can start your app local on your machine without apache, iis, etc..

## Requirements
You need follow components

1. nodejs
2. npm
3. nodejs express

You can download and install it via installer or as portable version

##How to host your application?
Clone this repository with git and put your openui5 application in components folder. If your application is hostet on git server, you can clone your repository in components folder.

##How to run
Go to your cloned repository order and run this:

    node app.js

followed by

    npm start

Your http server is running and your can see your app in browser at
http://127.0.0.1:3000/yourapplication

##thanks
[Creating a basic site with Node.js and Express](https://shapeshed.com/creating-a-basic-site-with-node-and-express/)