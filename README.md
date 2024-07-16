# Request Header Parser Microservice

This project is a simple Node.js and Express application that parses incoming request headers and returns specific information such as IP address, preferred language, and software details.

API Endpoint
/api/whoami
Example Response

```json
{
  "ipaddress": "127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"
}
```

## Setup and Installation

Clone the repository:
git clone https://github.com/your-username/request-header-parser.git
cd request-header-parser
Install dependencies:
npm install
Start the server:
npm start
The server will start on port 3000 by default.

### Usage

Make a GET request to /api/whoami to retrieve the request headers parsed into a JSON response.

### Technologies Used

Node.js
Express

### License

This project is licensed under the MIT License
