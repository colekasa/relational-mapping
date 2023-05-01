# E-Commerce Back End

This is the back-end for an e-commerce site, built using Express.js and Sequelize to interact with a MySQL database.

## Installation

To install the necessary dependencies, run:

npm install

## Usage

To start the server, run:

npm start

Once the server is running, you can use a tool like [Insomnia](https://insomnia.rest/) or [Postman](https://www.postman.com/) to make requests to the API. Here are the available routes:

- `GET /api/categories`: Returns a list of all categories.
- `GET /api/categories/:id`: Returns a single category with the specified ID.
- `POST /api/categories`: Creates a new category with the given data.
- `PUT /api/categories/:id`: Updates the category with the specified ID with the given data.
- `DELETE /api/categories/:id`: Deletes the category with the specified ID.

- `GET /api/products`: Returns a list of all products.
- `GET /api/products/:id`: Returns a single product with the specified ID.
- `POST /api/products`: Creates a new product with the given data.
- `PUT /api/products/:id`: Updates the product with the specified ID with the given data.
- `DELETE /api/products/:id`: Deletes the product with the specified ID.

- `GET /api/tags`: Returns a list of all tags.
- `GET /api/tags/:id`: Returns a single tag with the specified ID.
- `POST /api/tags`: Creates a new tag with the given data.
- `PUT /api/tags/:id`: Updates the tag with the specified ID with the given data.
- `DELETE /api/tags/:id`: Deletes the tag with the specified ID.

## Contribution

Feel free to contribute to this project by submitting pull requests or issues.

## License

This project is licensed under the MIT license.
