# Tims-PackageServer
Lightweight Package Server for WoltLab Community Framework

Install the dependencies:

$ npm install
Start the package server:

$ npm start
Create a folder named the same as the package identifier in packages:

$ mkdir packages/com.example.wcf.package
Drop the built archive named the same as the version number into the package folder:

$ cp com.example.wcf.package.tar packages/com.example.wcf.package/1.0.0.tar
Open the package server in the browser, your package should appear.
