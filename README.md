# -<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - My Portfolio Full Stack Project</title>
</head>
<body>
    <h1>My Portfolio Full Stack Project</h1>
    <p>This is a full-stack portfolio project built using HTML, CSS, JavaScript, Node.js, and MongoDB. It serves as a dynamic online portfolio that showcases my skills, projects, and allows visitors to contact me.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>Frontend:</strong>
            <ul>
                <li>Responsive and modern design</li>
                <li>Interactive sections showcasing projects and skills</li>
                <li>Contact form to allow users to reach out to me</li>
            </ul>
        </li>
        <li><strong>Backend:</strong>
            <ul>
                <li>RESTful API built with Node.js and Express</li>
                <li>MongoDB database to store user messages</li>
                <li>Basic CRUD operations for portfolio content management</li>
            </ul>
        </li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
        <li><strong>Backend:</strong> Node.js, Express.js, MongoDB, Mongoose (ODM)</li>
        <li><strong>Libraries and Frameworks:</strong> Bootstrap, FontAwesome</li>
    </ul>

    <h2>Installation</h2>
    <h3>1. Clone the Repository</h3>
    <pre><code>git clone https://github.com/haniajohar/-my-portfolio-full-stack-project.git</code></pre>
    <pre><code>cd my-portfolio-full-stack-project</code></pre>

    <h3>2. Install Dependencies</h3>
    <h4>Backend</h4>
    <pre><code>cd backend
npm install</code></pre>

    <h4>Frontend</h4>
    <pre><code>cd frontend
npm install</code></pre>

    <h3>3. Configure MongoDB</h3>
    <ul>
        <li>Ensure MongoDB is installed and running locally or use a cloud-based service like MongoDB Atlas.</li>
        <li>Update the connection string in the backend configuration file (e.g., `.env`) to match your MongoDB URI:</li>
        <pre><code>MONGO_URI=mongodb://localhost:27017/myportfolio</code></pre>
    </ul>

    <h3>4. Start the Application</h3>
    <h4>Backend</h4>
    <pre><code>cd backend
npm start</code></pre>

    <h4>Frontend</h4>
    <pre><code>cd frontend
npm start</code></pre>

    <h2>API Endpoints</h2>
    <ul>
        <li><strong>GET /api/users</strong> - Retrieve a list of users</li>
        <li><strong>POST /api/users</strong> - Add a new user</li>
        <li><strong>GET /api/projects</strong> - Retrieve a list of projects</li>
        <li><strong>POST /api/projects</strong> - Add a new project</li>
        <li><strong>GET /api/messages</strong> - Retrieve all messages from the contact form</li>
        <li><strong>POST /api/messages</strong> - Submit a new message from the contact form</li>
    </ul>

    <h2>Contributing</h2>
    <p>If you'd like to contribute to this project, feel free to fork it and create a pull request. All contributions are welcome!</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
