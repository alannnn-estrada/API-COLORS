# API-Colors

API-Colors is a simple Node.js application that provides color data in various formats (uppercase, lowercase) via different endpoints. You can also access the data by running the application locally or use the hosted API at [fl0.com](https://api-colors-4t6q-dev.fl0.io/api/colors/).

## Installation

To run this application locally, you need to have [Node.js](https://nodejs.org/) installed. After that, follow these steps:


1. Clone the repository:
  ```bash
  git clone https://github.com/alann-estrada/api-colors.git
  ```

2. Change to the project directory:

   ```bash
   cd api-colors
   ```

3. Install the required dependencies using npm:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   node server.js
   ```

The server should now be running on port 3000 or the port specified in your environment variables.

## API Endpoints

- `/api/colors`: Returns color data in the default format.
- `/api/colors/lowercase`: Returns color data with color names in lowercase.
- `/api/colors/uppercase`: Returns color data with color names in uppercase.

## Example Usage

To retrieve color data from the local server, you can use a tool like [curl](https://curl.se/) or a web browser:

- To get the default color data:

  ```bash
  curl http://localhost:3000/api/colors
  ```

- To get color data with lowercase color names:

  ```bash
  curl http://localhost:3000/api/colors/lowercase
  ```

- To get color data with uppercase color names:

  ```bash
  curl http://localhost:3000/api/colors/uppercase
  ```

## Dependencies

- [express](https://www.npmjs.com/package/express): Fast, unopinionated, minimalist web framework for Node.js.
- [cors](https://www.npmjs.com/package/cors): Middleware for enabling CORS (Cross-Origin Resource Sharing).

## License

This project is licensed under the ISC License.

Feel free to contribute, report issues, or use the API in your own applications. If you have any questions or need further assistance, please don't hesitate to reach out to me.

Thanks for using API-Colors!
