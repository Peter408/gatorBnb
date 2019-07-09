# GatorBnb

SFSU housing website project

This is a RESTful web application that function as housing website catered for Sfsu students. It allows users to rent, post, and email like message other users based on listing.

You may checkout the demo live at:
http://13.57.19.213/

# Development

## How to install Repository

Down the Repo:

```sh
git clone https://github.com/Peter408/gatorBnb.git
```

## How to Build and Set Up

- Navigate to root repo and run the following command to download all dependencies Express:

```sh
npm install
```

- Navigate to the /client and run the following command to download all dependencies for React:

```sh
npm install
```

- Set up the .env file with correct variable:

```sh
LOCAL_DATABASE_URL=postgres://username:password@host:port/database
BACKEND_URL=http://localhost:5000/api
```

- Migrate the database using Sequelize:

```sh
npm run db:migrate
```

- Seed the database by running:

```sh
npm run db:seed
```

## How to Run

- Run backend API in development by running the following command from root repo:

```sh
npm run start:dev
```

- Navigate to /client and run the following command to run React

```sh
npm start
```
