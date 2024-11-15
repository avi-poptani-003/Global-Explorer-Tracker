# Global Explorer Tracker

This is a simple web application that allows users to keep track of the countries they have visited. It uses Node.js, Express, and PostgreSQL to create a backend API that interacts with a database of countries and visited countries.

## Features

1. **View Visited Countries**: The home page displays a list of all the countries the user has visited, as well as the total number of countries visited.
2. **Add New Country**: Users can add a new country they have visited by entering the country name in the input field and clicking the "Add Country" button.
3. **Error Handling**: If the user tries to add a country that doesn't exist in the database or has already been added, the application will display an error message.

## Technologies Used

- **Node.js**: A JavaScript runtime environment that allows developers to run JavaScript on the server-side.
- **Express**: A popular web application framework for Node.js that simplifies the process of building web applications.
- **PostgreSQL**: An open-source relational database management system used to store the list of countries and the countries visited by users.
- **pg**: A PostgreSQL client for Node.js that provides a simple interface for interacting with the database.
- **bodyParser**: A middleware that parses incoming request bodies in JSON or URL-encoded format.
- **EJS (Embedded JavaScript)**: A templating engine that allows you to generate HTML with plain JavaScript.

## Setup and Installation

1. **Clone the repository**:
```bash
   git clone https://github.com/avi-poptani-003/Global-Explorer-Tracker.git
   ```
2. **Install dependencies**:
 ```bash
   cd your-folder
   npm install
   ```
    OR
```bash
   cd your-folder
   npm i
   ```
3. **Set up the PostgreSQL database**:
   - Install PostgreSQL on your system if you haven't already.
   - Create a new database named "world".
   - Update the `db.connect()` function in the `index.js` file with your PostgreSQL credentials.

4. **Run the application**:
```bash
   node index.js
   ```
   OR
```bash
   nodemon index.js
   ``` 
5. **Access the application**:
   - Open your web browser and go to `http://localhost:3000`.

## Usage

1. **View Visited Countries**: The home page will display a list of all the countries the user has visited, along with the total number of countries visited.
2. **Add New Country**: Enter the name of a country in the input field and click the "Add Country" button. If the country is found in the database and hasn't been added before, it will be added to the list of visited countries.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
