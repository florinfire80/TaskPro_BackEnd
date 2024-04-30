BackEnd for TaskPro project

Repositories:

Front-End:
Github: https://github.com/resinner/TaskPro-FrontEnd-Team6
Page: https://resinner.github.io/TaskPro-FrontEnd-Team6/

Back-End:
Github: https://github.com/AscariA10/TaskPro_API
Page: https://taskproapi-ukbi.onrender.com
Routes: https://taskproapi-ukbi.onrender.com/api-docs/#/

Description:
It's final, course team project. Our tasks were build WEB-app from scratch.

For BackEnd we used Node.js environment. As a database we used MongoDB for storage, and
Mongoose as a library for interaction with DB. For routing we use Express framework.
Also we implement possibility for saving user pictures in Cloudinary service.
Work with user mail's realized with nodemailer package and special account for this project.

How to clone project:

1. clone repository;
2. write npm i in terminal;
3. add .env file to your project;
4. next environmental variables are required:

- DB_HOST - your database connection link
- ACCESS_TOKEN_KEY - your key for access token
- REFRESH_TOKEN_KEY - your key for refresh token, for longer connection
- CLOUD_NAME , CLOUDINARY_API_KEY , CLOUDINARY_API_SECRET_KEY , CLOUDINARY_URL - your settings for cloudinary
  connection, where dashboard backgrounds and user avatars stored
- EMAIL_USERNAME , EMAIL_PASSWORD - settings for help window message in app.
