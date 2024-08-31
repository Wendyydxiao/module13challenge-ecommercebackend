
# E-Commerce Backend (ORM)

## Description
This project aims to build the back end for an e-commerce site for internet retailers to manage (create/update/delete) their product related information. It configures Express.js API to use Sequelize to interact with a PostgreSQL database. And all endpoints can be verified using Insomnia and able to reuse for other user interface.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation
- Ensure that Node.js & postgres sql are installed on your machine.
- Clone the repository to your local machine. 
- Run `npm install` to install the necessary dependencies (express,pg,squelize & dotenv).

## Usage
1. Open your terminal and navigate to the project directory.
2. Update `connection.js` to add your db name, postgres username & pasword to be connected to a database using Sequelize.
3. Run the command `psql -U postgres -f db/schema.sql` to create a new db.
4. Run the command `npm run seed` to seed sample data. 
5. Run the command `npm start`to invoke the application.
6. Get the correct API routes in Insomnia to test GET/POST/PUT/DELETE functions, the latest data will be reflected in your database instantly.

## License
This project is licensed under MIT.

## Contributing
Happy to have your contribution! Simply fork the repo and submit a pull request.

## Tests
Manual tests ran for this application.

## Questions
For questions, please contact me on GitHub at [wendyydxiao](https://github.com/wendyydxiao) or email me at wendyxiao1023@gmail.com.