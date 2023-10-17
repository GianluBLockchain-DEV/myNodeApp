Servizi Informatici Node.js Web App

This is a basic Node.js web application using the Express framework to serve a static HTML page along with stylesheets and scripts. The project includes a simple navigation structure based on an HTML template.

Installation:

1. Clone the repository:

   git clone <repository-url>

2. Navigate to the project directory:

   cd myNodeApp

3. Install dependencies:

   npm install

Usage:

1. Run the Node.js app:

   node index.js

2. Open your browser and go to http://localhost:3000 to view the web app.

Project Structure:

myNodeApp
|-- public
|   |-- images
|   |   `-- IT-Services.png
|   |-- style.css
|   |-- script.js
|   `-- index.html
|-- index.js
`-- package.json

- `public`: Contains static assets like images, stylesheets, and scripts.
- `index.js`: Entry point for the Node.js application.
- `package.json`: Configuration file with project metadata and dependencies.

Dependencies:

- Express: Fast, unopinionated, minimalist web framework for Node.js. [Express](https://expressjs.com/)

License:

This project is licensed under the MIT License - see the LICENSE file for details.
