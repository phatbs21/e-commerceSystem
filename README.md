
## Getting Started

### Prerequisites

- Node.js
- npm
- Sequelize CLI

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/e-commerceSystem.git
    cd e-commerceSystem
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up environment variables:
    - Copy [.env.example](http://_vscodecontentref_/7) to `.env` and update the values as needed.

4. Run database migrations:
    ```sh
    npx sequelize-cli db:migrate
    ```

### Running the Application

1. Start the server:
    ```sh
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`.

## Project Configuration

### Database Configuration

Database configuration is located in [config.json](http://_vscodecontentref_/8). Update this file with your database credentials.

### Environment Variables

Environment variables are managed using a `.env` file. Ensure you have all necessary variables defined in your `.env` file.

## Project Scripts

- `npm start`: Start the application.
- `npm run dev`: Start the application in development mode.
- `npm run build`: Build the application for production.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License.