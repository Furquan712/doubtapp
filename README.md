
# Doubt App

## Introduction

Doubt App is a community-driven platform where users can ask questions (doubts), provide answers, comment on existing threads, and vote on the helpfulness of contributions. Each question and answer can be tagged with relevant topics for easy navigation and categorization.

## Features

- **Ask Questions**: Users can post their doubts or questions on the platform.
- **Answer Questions**: Community members can provide answers to these questions.
- **Comment System**: Users can comment on both questions and answers for further discussion.
- **Voting Mechanism**: Upvote or downvote questions and answers based on their usefulness or accuracy.
- **Topic Tags**: Questions and answers can be tagged with topics for easy categorization and search.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before running this project, you need to have Node.js and npm installed on your machine. Visit [Node.js](https://nodejs.org/) to download and install them.

### Installing

Clone the repository to your local machine:

```
git clone [URL of your project repository]
```

Navigate to the project directory:

```
cd doubtapp
```

#### Setting Up the Client

```
cd client
npm install axios jwt-decode moment react-copy-to-clipboard react-router-dom redux react-redux redux-thunk
```

#### Setting Up the Server

```
cd server
npm install bcryptjs jsonwebtoken cors dotenv express mongoose nodemon
```

### Running the Application

After installing the dependencies for both the client and server, you can run the application:

```
// For the client
cd client
npm start

// For the server
cd server
npm run start
```

 
