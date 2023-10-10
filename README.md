# Patient Registration System

This project is a simple patient registration system built with React for the frontend and Express.js with MongoDB for the backend. The application collects patient information through a multi-step form, validates the input, transforms it into a FHIR-compliant format, and stores it in a MongoDB database. The stored data is then retrieved, decrypted, and displayed back to the user.

## Features

- Multi-step form with field validation.
- Data transformation to FHIR format.
- Data encryption before saving to the database.
- Decryption of data before sending it back to the client.
- Display of saved data to the user.

## Prerequisites

Ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/en/) (v14.x or later)
- [MongoDB](https://www.mongodb.com/try/download/community) (v4.x or later)

## Setup

Clone the repository to your local machine:

```bash
git clone https://github.com/DaveM0820/patient-registration-system.git
```

Navigate to the project directory:

```bash
cd patient-registration-system
```

### Backend Setup

Navigate to the server directory:

```bash
cd server
```

Install the necessary dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

The server will start on [http://localhost:3001](http://localhost:3001).

### Frontend Setup

In a new terminal, navigate to the client directory from the project root:

```bash
cd client
```

Install the necessary dependencies:

```bash
npm install
```

Start the client:

```bash
npm start
```

The application will open in your web browser at [http://localhost:3000](http://localhost:3000).

## Usage

1. Navigate to [http://localhost:3000](http://localhost:3000) in your web browser.
2. Fill out the form fields in each step and click "Next" to proceed.
3. Review the summary of provided information in the final step.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
```