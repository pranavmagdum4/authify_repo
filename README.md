# Description
This project implements user authentication and registration
features using JSON Web Tokens (JWT) in a full-stack application 
built with Node.js, Express.js, React.js, and MySQL. 
The primary focus is on enhancing security by 
mitigating common web vulnerabilities such as Cross-Site Scripting (XSS) 
and Cross-Site Request Forgery (CSRF) attacks.

## Installation

### Backend (Node.js/Express + MySQL)

1. Clone the repository to your local machine:

```bash
git clone <repository-url>
```    

2.Navigate to the backend directory:

```bash
cd backend
```

3.Install dependencies:

```bash
npm install
```

4.Configure the environment variables:

Create a .env file in the root of the backend directory.
Add the required environment variables (e.g., database connection details, JWT secret).

5.Start the backend server:

```bash
nodemon index
```

### Frontend (React.js)
1. Navigate to the frontend directory:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend development server:

```bash
npm start
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
