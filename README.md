# DeepCast

DeepCast is a comprehensive platform designed to streamline the process of creating, managing, and distributing podcasts and YouTube videos. This project leverages modern web technologies to provide a seamless experience for content creators.

## Features

- **Podcast Management**: Easily upload, edit, and manage your podcast episodes.
- **YouTube Integration**: Sync your content with YouTube, including video uploads and metadata management.
- **Analytics**: Track the performance of your content with detailed analytics.
- **User Authentication**: Secure user authentication and authorization.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Project Structure

The project is divided into three main parts:

1. **Frontend**: Built with React and Vite, the frontend provides a user-friendly interface for managing content.
2. **Backend**: Powered by Express and TypeScript, the backend handles API requests, user authentication, and data management.
3. **AI Service**: A separate service for handling AI-related tasks, such as transcription and content recommendations.

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Python (for AI service)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/DeepCast.git
    cd DeepCast
    ```

2. Install dependencies for the frontend:
    ```sh
    cd frontend
    npm install
    ```

3. Install dependencies for the backend:
    ```sh
    cd ../backend
    npm install
    ```

4. Install dependencies for the AI service:
    ```sh
    cd ../ai-service
    pip install -r requirements.txt
    ```

### Running the Project

1. Start the backend server:
    ```sh
    cd backend
    npm run dev
    ```

2. Start the frontend development server:
    ```sh
    cd ../frontend
    npm run dev
    ```

3. Start the AI service:
    ```sh
    cd ../ai-service
    python main.py
    ```

### Environment Variables

Create a `.env` file in the root of each service ([backend](http://_vscodecontentref_/1) and [ai-service](http://_vscodecontentref_/2)) and add the necessary environment variables. Refer to the `.env.example` files for the required variables.

### Building for Production

1. Build the frontend:
    ```sh
    cd frontend
    npm run build
    ```

2. Build the backend:
    ```sh
    cd ../backend
    npm run build
    ```

## Contributing

Contributions are welcome! To contribute to this project, follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/DeepCast.git
    cd DeepCast
    ```
3. Create a new branch for your feature or bugfix:
    ```sh
    git checkout -b feature-or-bugfix-name
    ```
4. Make your changes and commit them with a descriptive message:
    ```sh
    git add .
    git commit -m "Description of the feature or bugfix"
    ```
5. Push your changes to your forked repository:
    ```sh
    git push origin feature-or-bugfix-name
    ```
6. Create a pull request on the original repository, describing your changes and why they should be merged.

Please read the CONTRIBUTING.md for more detailed guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Python](https://www.python.org/)

## Contact

For any inquiries or feedback, please contact [yourname@example.com](mailto:selva.p@somaiya.edu).

