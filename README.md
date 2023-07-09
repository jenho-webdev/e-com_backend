# E-commerce Backend

This is the backend for an e-commerce application. It provides the server-side functionality for managing products, categories, and tags. The backend is built with Node.js, Express.js, and Sequelize ORM.

- [Explore the docs]( https://github.com/jenho-webdev/e-com_backend)

- [Report Bug](https://github.com/jenho-webdev/e-com_backend/issues/)

- [Request Feature](https://github.com/jenho-webdev/e-com_backend/issues)

## Table of Contents

- [E-commerce Backend](#e-commerce-backend)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [API Endpoints](#api-endpoints)
  - [Demo](#demo)
  - [Contributing](#contributing)
  - [License](#license)
  - [Credits](#credits)
  - [Contact](#contact)

## Features

- CRUD operations for products, categories, and tags
- Associations between products, categories, and tags
- RESTful API endpoints
- Error handling and response status codes
- Database seed files for testing and development

## Installation

1. Clone the repository:

```bash
   git clone https://github.com/jenho-webdev/e-com-backend.git
```

2. Install dependencies


```bash
cd e-commerce-backend
npm install
```

3. Set up the database

Create a MySQL database and update the configuration in config/config.json

Run the database migrations

```bush
npx sequelize-cli db:migrate
```

4.  Seed the database with sample data

```bush
npx sequelize-cli db:seed:all
```

5. Start the server

```bush
npm start
```


The server will be running at `http://localhost:3001`. You can test the API endpoints using a tool like Postman or curl.

## API Endpoints

- **GET /api/products**: Get all products.
- **GET /api/products/:id**: Get a single product by ID.
- **POST /api/products**: Create a new product.
- **PUT /api/products/:id**: Update a product by ID.
- **DELETE /api/products/:id**: Delete a product by ID.

- **GET /api/categories**: Get all categories.
- **GET /api/categories/:id**: Get a single category by ID.
- **POST /api/categories**: Create a new category.
- **PUT /api/categories/:id**: Update a category by ID.
- **DELETE /api/categories/:id**: Delete a category by ID.

- **GET /api/tags**: Get all tags.
- **GET /api/tags/:id**: Get a single tag by ID.
- **POST /api/tags**: Create a new tag.
- **PUT /api/tags/:id**: Update a tag by ID.
- **DELETE /api/tags/:id**: Delete a tag by ID.


## Demo

The following video demo the application being used from the command line:
[![demo video on v2](./assets/video-thumbnail.png)](https://youtu.be/mpTVedbQKSE)

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [![MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://github.com/jenho-webdev/ERM/blob/main/LICENSE)

> For details of the application's licensing details, please visit the License page in the repo [here](https://github.com/jenho-webdev/ERM/blob/main/LICENSE)
>
>
In the above example, the "Configuration" section explains how to set up the environment variables using the `.env` file and references the `.env.example` file as a template. It also emphasizes the importance of not committing the `.env` file to version control and includes a note to add it to the `.gitignore` file.

Feel free to modify and adapt this example to fit your specific project requirements.



## Credits

Simple ERM was created by me as part a coding challenge for the UCI Full Stack bootcamp course assignment related to topics on OOP, node js., Express.js, Heroku deployment, and more.

The development of this program was supported by the course materials and resources provided by the bootcamp.

Shield and badges used in this markdown document were sourced from Shields.io.

## Contact

For any inquiries or questions, welcome to contact me @
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/jen-h-202a1723/)[![Github][Github-shield]](https://github.com/jenho-webdev/Personal-Portfolio)[![Slack][slack-shield]](https://jenworkspace-as73396.slack.com/archives/C052QLTJQHG)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[Github-shield]:https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
[slack-shield]:https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white

