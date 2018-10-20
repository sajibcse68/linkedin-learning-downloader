# LinkedIn Learning Downloader
JavaScript script to Download videos, transcripts and exercise files from LinkedIn Course!

## How it works

You need a Linkedin Premium Account.<br/>
You need to have Node.js installed.<br/>
Download the project.<br/>
Open the terminal in the project folder and type:

```sh
npm install
```

to download necessary modules. (N.B. Puppeteer is a biiiig module).<br/>
Modifiy the .env file adding your Linkedin username(email) and password.<br/>
In order to properly set the LINKEDIN_COURSE, open the course you are interested in, e.g.:

```sh
# put 'learning-react-js-2018' if url is 
https://www.linkedin.com/learning/learning-react-js-2018
```

```sh
$ node-js-deploying-applications
```
Now, execute the index.js file to download the course:

```sh
$ node ./index.js
```
