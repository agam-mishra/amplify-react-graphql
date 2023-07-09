# Simple Notes App with AWS Amplify📝

Welcome to the Simple Notes App project! This project aims to help you build a simple notes application using AWS Amplify. The app will have authentication, hosting, database, storage, and image upload capabilities, allowing users to create, view, and manage their notes along with attached images.

## Features

- User authentication: Users can sign up, sign in, and securely access their notes.
- Hosting: The application will be hosted on AWS, making it accessible globally.
- Database: AWS Amplify will provide a managed database for storing notes.
- Storage: Users can upload and store attachments or images for their notes.
- Image Upload: Users can attach images to their notes, enhancing the note-taking experience.

## Prerequisites

Before you start, ensure you have the following:

- Basic knowledge of JavaScript and React.
- An AWS account with administrator-level access.
- Node.js and npm installed on your machine.

## Installation and Setup

To set up the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/agam-mishra/notes-app.git
   cd notes-app
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

3. Set up AWS Amplify:

   ```bash
   amplify init
   ```

   Follow the prompts to configure your Amplify project. Choose the desired options for your authentication, hosting, database, and storage configurations.

4. Deploy the AWS Amplify resources:

   ```bash
   amplify push
   ```

   This command will provision the necessary resources on AWS for hosting, authentication, database, and storage.

## Usage

To start using the Simple Notes App, follow these steps:

1. Start the application:

   ```bash
   npm start
   ```

   This will start the development server and open the app in your default browser.

2. Sign up for a new account or sign in with an existing one.

3. Create, view, edit, or delete notes as needed.

4. Upload attachments or images to your notes by selecting the appropriate option when creating or editing a note.

## Architecture

The Simple Notes App uses the following AWS Amplify services:

- Authentication: AWS Cognito
- Hosting: AWS S3 and AWS CloudFront
- Database: AWS DynamoDB
- Storage: AWS S3

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
