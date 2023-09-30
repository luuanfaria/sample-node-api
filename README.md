
# Basic Node.js Project Structure

This is a simple Node.js project that demonstrates a basic structure for creating an API. It includes a user controller, a body parser, sample user data, and routes.

## Folder Structure

The project is organized into the following folders:

- `src/`: The main project folder.
  - `controllers/`: Contains controllers to handle API operations.
    - `userController.js`: User controller with basic CRUD operations.
  - `helpers/`: Contains utility functions.
    - `bodyParser.js`: Body parser to process JSON request data.
  - `mocks/`: Contains sample data.
    - `users.js`: Sample user data.
  - `index.js`: The main file that creates the HTTP server and sets up routes.
  - `routes.js`: Defines API routes and associates them with the appropriate controllers.

## How to Run

Make sure you have Node.js installed on your system.

1. Clone this repository to your machine:

   ```shell
   git clone https://github.com/luuanfaria/sample-node-api.git
   ```

2. Navigate to the project folder:

   ```shell
   cd your-node-project
   ```

3. Install dependencies:

   ```shell
   npm install
   ```

4. Start the server:

   ```shell
   npm start
   ```

The server will be running at http://localhost:3000. You can access the routes defined in `routes.js` to interact with the API.

## API Routes

- `GET /users`: Returns the list of users.
- `GET /users/:id`: Returns a user by ID.
- `POST /users`: Creates a new user.
- `PUT /users/:id`: Updates a user by ID.
- `DELETE /users/:id`: Deletes a user by ID.

Be sure to check the `userController.js` file for detailed implementations of API operations.

## Contribution

Feel free to contribute improvements or fixes to this project. Just fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Created by Luan

<p align="center">
  <samp>
    <a href="https://luuanfaria.dev">website</a> .
    <a href="https://linkedin.com/in/luuanfaria">linkedin</a> .
    <a href="https://twitter.com/luuanfariaf">twitter</a> .
  </samp>
</p>