# E-Commerce Back End


[![License: MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/license/mit/)

## Table of Contents

 * [Description](#description)

 * [Installation](#installation)

 * [Usage](#usage)

 * [Contributing](#contributing)

 * [Credits](#credits)

 * [Tests](#tests)

 * [License](#license)

 * [Questions](#questions)

## Description

Built the back end for an e-commerce site by modifying starter code. Configured a working Express.js API to use Sequelize to interact with a MySQL database.

## Installation

You must first clone this repo. Once the repo is downloaded, open it in VS Code. <br />
Rename the .envEXAMPLE environment variables file to .env and store your MySQL username and password within. <br />
Install Node.js modules, including the Sequelize, Express, dotenv and MySQL2 dependencies, using the terminal command:
```console
npm i
```
Log in to your MySQL.
```console
mysql -u USER -p
PASSWORD
```
Create the database.
```console
source db/schema.sql
exit
```
Seed the database.
```console
npm run seed
```
Run the application using the terminal command:
```console
node server.js
```

## Usage

With the database created and seeded and the server running, you may use Insomnia to test the GET, POST, PUT, and DELETE routes. <br />
[Link to demonstration video]()

## Contributing

Contributors: <br />

- [Ryan Gurley](https://github.com/gurleyryan)

## Credits

External Sources: <br />
- [Node.js](https://nodejs.org/en) <br />
- [Express.js](https://www.npmjs.com/package/express) <br />
- [MySQL2](https://www.npmjs.com/package/mysql2) <br />
- [Sequelize](https://www.npmjs.com/package/sequelize) <br />
- [dotenv](https://www.npmjs.com/package/dotenv) <br />
- [Insomnia](https://insomnia.rest/)

## Tests

N/A

## License

MIT License

## Questions

Have additional questions? Contact me through my GitHub or email.

[Link to Github](https://github.com/gurleyryan)

<a href="mailto:gurleyryan@gmail.com">gurleyryan@gmail.com</a>
