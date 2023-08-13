# Daily Journal/Blog App

A web application for writing and reading daily journal/blog articles.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Description

This project is a web application that allows users to write and read daily journal/blog articles. The main features include a home page displaying a list of article titles and snippets, and an article page with the full content of each article. The articles are stored and retrieved from a MongoDB database.

## Features

- View a list of article titles and snippets on the home page
- Click on "read more" to view the full content of an article
- Add new articles to the database
- Retrieve articles from the MongoDB database

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/your-daily-journal-app.git`
2. Navigate to the project directory: `cd your-daily-journal-app`
3. Install dependencies: `npm install`
4. Define the following environment variables in the `.env` file:

   ```plaintext
   PORT=3000
   ADM_NAME=YourUserNameInMongoDB
   ADM_PASSWORD=yourPasswordInMongoDB

## Usage

1. Start the server: `npm start` or `nodemon`
2. Open your web browser and go to: `http://localhost:3000`
3. Browse and read existing articles or create new ones

## Technologies

- Node.js
- Express.js
- MongoDB
- EJS (Embedded JavaScript) templates

## Dependencies

- body-parser: ^1.20.2
- dotenv: ^16.3.1
- ejs: ^3.1.9
- express: ^4.18.2
- lodash: ^4.17.11
- mongodb: ^5.7.0
- mongoose: ^7.4.2
- nodemon: ^3.0.1

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Author

[pan.be](https://business-card-pan-be.netlify.app)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
