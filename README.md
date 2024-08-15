# URL Shortener
This is a simple URL Shortener built using Node.js. It allows you to shorten long URLs and access them using a short URL. The application does not include a graphical user interface (GUI) and is designed for use via HTTP requests.

## Features
1. Shorten long URLs into short, easy-to-share links.
2. Redirect short URLs to the original long URLs.
3. Simple, lightweight, and easy to deploy.

## Requirements
1. Node.js (version 12 or higher)
2. npm (Node Package Manager)

## Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/url-shortener.git
cd url-shortener
```

2. Install the dependencies:
```
npm install
```

3. Start the server:
```
npm start
```

The server will start on http://localhost:8001.

## Usage
1. Shorten a URL
   
Method: POST

Request Body:
```json
{
  "url": "https://www.google.com"
}
```

Response:
```json
{
  "id": "efBqmF8qj"
}
```

2. Access a Shortened URL
   
Method: GET

Example:
Visiting http://localhost:8001/efBqmF8qj will redirect to https://www.google.com.

## Contributing
Feel free to contribute by submitting a pull request. Please ensure your code follows the project's coding guidelines and includes appropriate tests.


Created By PUNEET
