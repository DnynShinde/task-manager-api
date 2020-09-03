# task-manager-api

### Task manager API using nodejs. This is just a backend. Use Postman or similar client to make requests.

1. Express JS
1. MonogoDB + Mongoose

> Hosted at: [Task manager API](https://dbs-task-manager.herokuapp.com/) This link won't open. (Use Postman to make requests.)

### Usage

Add 'config' folder in project root. Add 'config/dev.env':
```env
PORT=3000
MONGODB_URL=Your_mongodb_url
JWT_SECRET=Your_jwt_secret
```
Install dependencies:
```bash
npm install
```

Run script:
```bash
npm run dev # Server (:3000)
```
