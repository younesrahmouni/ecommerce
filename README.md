### 1. Create .env file
- Create .env file in project folder
- Enter these lines to that after creating the database:

```
MONGODB_URL=mongodb://localhost/JonasShop
```

### 2. Run Backend

```
$ npm install
$ npm run build
$ npm start
```

### 3. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 4. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- Note admin email and password

### 5. Admin Login

- Run http://localhost:8080/#/signin
- Enter admin email and password and click signin
- Click Dashboard Link on Header Menu
- Click Products on left sidebar
- Click Create Product Button
- Enter Product Information
- Go to home page (http://localhost:8080) and test Ecommerce Website
