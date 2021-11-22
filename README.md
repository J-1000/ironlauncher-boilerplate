### Change the name of the database in db/index.js

```js
// db/index.js

const MONGO_URI = process.env.MONGODB_URI || "mongodb://localhost/< name of the db>";
```