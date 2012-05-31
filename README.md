Sencha-Core-build
=================

A jsb3 file to help you rebuild the SenchaTouch package to get core features (without UI features) and make it works with other Mobile HTML5 frameworks.

The target of this build process is "creating a custom version of SenchaTouch - which I called Sencha Core" that support below features:

1) touch-core-prod.js
+ Sencha Class system and the dynamic class loading mechanism.
+ Dom querying/accessing

2) touch-extra-prod.js
+ Ajax
+ Data model
+ JSON, XML parsing
+ Logging
+ Storage
+ Utilities features

How to use it?
=================
This jsb3 file is customized from the final version of SenchaTouch package (2.0.1) currently. 

You need to follow below steps to use it or you can get 2 final output files in the output folder to use in your project.

Step 1: Download Sencha SDK tool at http://www.sencha.com/products/sdk-tools. Install it. This tool currently can work on Windows.

Step 2: Download Sencha Touch at http://www.sencha.com/products/touch/ 

Step 3: Copy the sencha-core-mobile.jsb3 to your SenchaTouch folder

Step 4: Create an output folder on your computer. Open command line and run below command:

sencha build -p "Your SenchaTouch folder\sencha-core-mobile.jsb3" -d "Your output folder"

After running the build, you will get 2 output files in the output folder:
+ touch-core-prod.js
+ touch-extra-prod.js
