
# Bug-Bounty-Platforms

**Bug-Bounty-Platforms** is an open-source platform designed to facilitate and manage bug bounty programs. This tool helps organizations run their bug bounty programs efficiently while providing a seamless experience for security researchers to report vulnerabilities.

## Features

- **Program Management**: Create and manage bug bounty programs with customizable scopes and reward structures.
- **Vulnerability Reporting**: Allow researchers to submit detailed vulnerability reports with attachments and evidence.
- **Secure Communication**: Enable secure messaging between researchers and program managers.
- **Tracking and Management**: Track the status of reports, manage submissions, and handle reward distributions.
- **API Integration**: Integrate with other tools and platforms using our RESTful API.
- **Dashboard**: View real-time statistics and manage all aspects of the bounty program from a comprehensive dashboard.

## Technologies

- **Frontend**: Built with React for a responsive and dynamic user interface.
- **Backend**: Powered by Node.js and Express for scalable and efficient server-side operations.
- **Database**: Utilizes PostgreSQL for reliable and structured data storage.
- **Authentication**: Secure authentication using JWT (JSON Web Tokens).
- **Deployment**: CI/CD pipelines with GitHub Actions; deployment on AWS.

## Getting Started

To get started with **Bug-Bounty-Platforms**, follow the instructions below:

### Prerequisites

- Node.js (v14 or higher)
- PostgreSQL (v12 or higher)
- Docker (optional, for containerized deployment)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Bug-Bounty-Platforms.git
   cd Bug-Bounty-Platforms
   ```

2. **Set Up Backend**

   - Navigate to the backend directory:

     ```bash
     cd backend
     ```

   - Install dependencies:

     ```bash
     npm install
     ```

   - Set up environment variables. Create a `.env` file based on `.env.example` and configure your settings.

   - Run the backend server:

     ```bash
     npm start
     ```

3. **Set Up Frontend**

   - Navigate to the frontend directory:

     ```bash
     cd ../frontend
     ```

   - Install dependencies:

     ```bash
     npm install
     ```

   - Run the frontend application:

     ```bash
     npm start
     ```

4. **Database Setup**

   - Ensure PostgreSQL is running and create a database for the project.
   - Run database migrations to set up the schema:

     ```bash
     cd ../backend
     npm run migrate
     ```
