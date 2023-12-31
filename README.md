# URL Shortener

A URL shortening service built with Node.js, Express.js, and MongoDB.

## Description

This project provides a simple URL shortening service that allows users to generate shortened URLs for long web addresses. It utilizes a MongoDB database to store the original and shortened URLs. A user can navigate to the shortened URL and access the original longer web address, location. Enjoy! 

Note: This database is purged daily.

### Sample Request Body

{
    "url": "https://www.youtube.com/watch?v=khPrXEEEp6E"
}

### Sample Response Body

{
    "originalUrl": "https://www.youtube.com/watch?v=khPrXEEEp6E",
    "shortCode": "krjpLf1",
    "newUrl": "http://localhost:8001/krjpLf1",
    "_id": "6544857c79d15c8a38ff12e4",
    "__v": 0
}

## Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.

## Usage

To start the server, use the following command:

npm run dev

The server will start on the specified port, and you can access the URL shortening service from your browser or any API testing tool.

### Dependencies

- cors: ^2.8.5
- dotenv: ^16.3.1
- express: ^4.18.2
- helmet: ^7.0.0
- http: ^0.0.1-security
- mongodb: ^6.2.0
- mongoose: ^7.6.4
- randomstring: ^1.3.0

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Bernard Major

Feel free to reach out if you have any questions or need support with the project.
