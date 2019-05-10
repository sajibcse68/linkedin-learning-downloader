# LinkedIn Learning Downloader
JavaScript script to Download videos, transcripts and exercise files from LinkedIn Course!

## How it works

- You need a LinkedIn Premium Account.
- You need to have Node.js installed.
- Clone the Repository


#### Download All Dependencies

Go to the project directory using terminal & run

```sh
npm install
```

#### Update the `.env` file adding your Linkedin username(email), password, course-url

```sh
LINKEDIN_EMAIL=<email>
LINKEDIN_PASSWORD=<password>
LINKEDIN_COURSE=<course-url>
# put LINKEDIN_COURSE=learning-react-js-2018 if url is https://www.linkedin.com/learning/learning-react-js-2018
```

#### Download the course!

```sh
$ node ./index.js
```
