# DevConnector 2

An app for persisting users and user posts. Created with React, Redux, MongoDB, Express, Bootstrap and a few other NodeJs packages.

This was created following a Udemy course by Brad Traversy, called MERN stack. This includes custom adjustments and bug fixes.

To use this, create two files in _./config/_: **default.json** and **production.json**, with each having the following content:

```js
{
  "mongoURI": "YOUR_MONGODB_ATLAS_URI",
  "jwtSecret": "YOUR_PREFERRED_ANY_SECRET_TOKEN",
  "githubClientId": "YOUR_GITHUB_CLIENT_ID",
  "githubSecret": "YOUR_GITHUB_SECRET"
}
```

Replace `mongoURI`, `jwtSecret`, `githubClientId`, and `githubSecret` values in both files with your MongoDB database URI and github information.

The server and client can then be hosted at Heroku.

See [devconenctor_2.0](https://github.com/bradtraversy/devconnector_2.0)
