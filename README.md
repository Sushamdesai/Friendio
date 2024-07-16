Friendio
Friendio is a robust social media application developed using the PERN stack (PostgreSQL, Express.js, React.js, Node.js). This project provides features such as secure user authentication, picture sharing, and interactivity through likes and comments.

Features
User Authentication: Secure login and registration system.
Picture Sharing: Users can post and share pictures.
Interactivity: Users can like and comment on posts and pictures.
Technologies Used
Frontend: React.js
Backend: Node.js, Express.js
Database: PostgreSQL
Styling: Tailwind CSS
Setup and Installation
To get a local copy of Friendio up and running, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/friendio.git
cd friendio
Add node_modules to .gitignore:

Ensure your .gitignore file includes node_modules/ to prevent the folder from being pushed to GitHub.

plaintext
Copy code
node_modules/
Remove node_modules from Git tracking (if already added):

bash
Copy code
git rm -r --cached node_modules
Install dependencies:

Using npm:

bash
Copy code
npm install
Or using yarn:

bash
Copy code
yarn install
Set up the database:

Create a PostgreSQL database and configure the connection in your environment variables.

plaintext
Copy code
DATABASE_URL=your_database_url
Run the development server:

bash
Copy code
npm start
Or using yarn:

bash
Copy code
yarn start
