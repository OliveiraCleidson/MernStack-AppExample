# This Project is a study object

Watching a tutorial of youtube, I have learned some fundamentals.
> https://www.youtube.com/watch?v=7CqJlxBYj-M

## To Run Locally after Git Clone and NPM Install, in root folder
```sh
$ npm start
```

In backend folder
```sh
$ node server.js
```

or

```sh
$ nodemon server.js
```

### For Run Locally is necessary configure MongoDB connection
Create a file '.env' in backend folder, write in file:
```sh
ATLAS_URI=mongodb+srv://<dbUser>:<dbUserPassword>@<url>
```