# Vidly API

![Version][version-image]
![License][license-image]

Vidly is an imaginary service for renting out movies, being a project developed to apply the concepts covered during the [Node.js: The Complete Guide to Build RESTful APIs (2018)](https://www.udemy.com/course/nodejs-master-class/) course on Udemy.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Node.js `>=` v10.16.3;
* npm `>=` v6.9.0;

### Installing

1. Clone this repository: `git clone https://github.com/FABJNR/vidly-api.git`;
2. Install dependencies: `npm install`;
3. Rename the `.env.example` file to `.env`;
    * _To make your own changes, please create your cluster in [MongoDB Atlas](https://www.mongodb.com/)._
    * Change the database connection string in the `.env` file, replacing **`your-mongodb-connect-here`** with your connection string.
    ```env
    MONGO_DB_CONNECTION_STRING=your-mongodb-connect-here
    ```
4. Run `npm run dev` to start the application in development mode.
    * The application will run at `http://localhost:3000`;

## Built With

* [Express](https://expressjs.com/) - Node.js web application framework.
* [@hapi/joi](https://hapi.dev/family/joi/) - Object schema validation.
* [dotenv](https://github.com/motdotla/dotenv#readme) - Module that loads environment variables from a `.env` file into [`process.env`](https://nodejs.org/docs/latest/api/process.html#process_process_env).
* [mongoose](https://mongoosejs.com/) - Elegant mongodb object modeling for node.js.

## Release History

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/FABJNR/vidly-api/tags).

* 0.1.2
    * CHANGE: Add persistence to Genre API
* 0.1.1
    * CHANGE: Project restructuring
* 0.1.0
    * Build the Genres API

## Authors

* **Fernando Albuquerque** - *Initial work* - [FABJNR](https://github.com/FABJNR)

## License

This project is licensed under the MIT License - see [LICENSE](https://github.com/FABJNR/vidly-api/blob/master/LICENSE) for more information.

<!-- Markdown link & img dfn's -->
[version-image]: https://img.shields.io/badge/version-v0.1.2-informational?style=flat-square
[license-image]: https://img.shields.io/badge/license-MIT-green?style=flat-square
