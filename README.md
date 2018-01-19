## Intro
It's an demo for uploading large file to Google Drive with util library(util.js)
and part of it came from this quickstart tutorial
(https://developers.google.com/drive/v3/web/quickstart/nodejs)

To run the demo,  
1. one should first prepare client secret file, and
these are the steps for getting this file:  
a. Use this wizard to create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to credentials.  
b. On the Add credentials to your project page, click the Cancel button.
 c. At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button.  
d. Select the Credentials tab, click the Create credentials button and select OAuth client ID.  
e. Select the application type Other, enter the name "Drive API Quickstart", and click the Create button.  
f. Click OK to dismiss the resulting dialog.  
g. Click the file\_download (Download JSON) button to the right of the client ID.  
h. Move this file to your working directory and rename it client_secret.json.  
2. After you get the secret file, change the comment "put the file you want to upload" to an actual file path.  
3. install the dependencies by typing `npm install`  
4. run the test script by typing `node testUpload.js`  

if one want to change the save location of token,
it can be set in config.js

## Credit

* resumableUpload.js came from here
https://gist.github.com/dam1/f77fcbea52ca9124ff50f3598d280710

* and related source:
https://github.com/grayleonard/node-youtube-resumable-upload/blob/master/index.js