# RESTful API with Express and MongoDB

This is a Node.js RESTful API using Express and MongoDB.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js, npm, and MongoDB installed on your local machine.

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

### Installing

1. Clone the repository:
   ```bash
   git clone https://github.com/coderooz/rest-api.git
   cd rest-api
   ```

2. Install the dependencies:
   ```bash
   npm install express mongoose body-parser
   ```

3. Start MongoDB:
   ```bash
   mongod
   ```

4. Start the server:
   ```bash
   node index.js
   ```

5. The API will be available at `http://localhost:3000`.

### API Endpoints

- `GET /api/items` - Retrieve all items
- `POST /api/items` - Create a new item
- `PUT /api/items/:id` - Update an item by ID
- `DELETE /api/items/:id` - Delete an item by ID

### Built With

- [Express](https://expressjs.com/) - The web framework used
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling tool
- [Body-parser](https://www.npmjs.com/package/body-parser) - Node.js body parsing middleware

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Authors

- **Ranit Saha** - *Initial work* - [coderooz](https://github.com/coderooz)

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
