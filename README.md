<h1>
    STOREFRONT API
</h1>

Menu:&nbsp;&nbsp;
[About](#âš%EF%B8%8F-about) |
[Packages](#-packages) |
[Folder structure](#-folder-structure) |
[Getting started](#-getting-started)  

## âšī¸ About

<p>
    For our second milestone project, we are tasked with creating an api to provide all the functionality need for an online store.
</p>

## đĨ Packages

The project was started with the following packages:

- [NodeJS](https://nodejs.org/)
- [ExpressJS](https://expressjs.com/)
- [Typescript](https://www.typescriptlang.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Jasmine](https://jasmine.github.io/index.html)
- [ESLint](https://eslint.org/)
- [Prettier Code Formatter](https://prettier.io/)
- [Dotenv](http://npmjs.com/package/dotenv)

In the dev dependencies the Jasmine, Eslint and Prettier are configured.

## đ Folder structure
```
âââ dist
âââ migrations
â   âââ sqls (contains SQL migration files)
âââ spec
â   âââ support (contains jasmine.json file)
âââ src (main application folder)
â   âââ handlers (contains the controller/logic for the endpoints)
â   âââ middlewares (folder for middleware > such as verifyToken middleware)
â   âââ models (folder for database models)
â   â   âââ tests (folder for Jasmine test is within the models folder)
â   âââ services (folder for dashboard logic)
â   âââ database.ts (database connection file)
â   âââ server.ts (entry point of the API)
|  
âââ .eslintignore (file that contains what should be ignored by ESLint)
âââ .eslintrc (ESLint configuration file)
âââ .gitignore
âââ .prettierrc (Prettier configuration file)
âââ database.json (database configuration file)
âââ package-lock.json
âââ package.json
âââ tsconfig.json (configuration file to Typescript)
```

## đ Getting started

First of all you need to have `node` and `npm` installed on your machine.

Fork and Clone this repository to your local machine.

Then navigate into the cloned project folder, and run: `npm install`.

Create a .env file and set the following variables:

```
PORT=ANY_CHOOSEN_PORT // this is optional, it uses PORT=3000 by default
POSTGRES_HOST=YOUR_HOST
POSTGRES_DB=YOUR_DATABASE_NAME
POSTGRES_TEST_DB=YOUR_TEST_DATABASE
POSTGRES_USER=YOUR_DATABASE_USERNAME
POSTGRES_PASSWORD=YPUR_PASSWORD
NODE_ENV=dev
TOKEN_SECRET=A_SECRET_FOR_YOUR_TOKEN
BCRYPT_PASSWORD=A_SECRET_FOR_BRCYPT_ENCRYPTION
SALT_ROUNDS=10

```
* Note: You should create a database and test database for the API (with the names matching your variables in the .env file)

Then edit the database.json file accordingly.

Then start the project by running: `npm run start`.

To run the tests, after the dependencies are installed, run `npm run test`.

See the RESTful routes for the required endpoints in the REQUIREMENTS.md file [here](REQUIREMENTS.md).

## Version History

* 1.0
    * Initial Release

---

### Made with đ by Abubakar Sadiq Sambo
## đ Let's connect
* [Portfolio](https://sadiqsambo.netlify.app)
* LinkedIn: [Abubakar Sambo](https://www.linkedin.com/in/sadiqsambo/)
* Twitter: [@_abubakarSambo](https://twitter.com/_abubakarSambo/)

