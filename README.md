# CC-CareerG.
This repo is a SQL TS/React environment || Created for Log In, Log out, Sign Up Pages || Authenticators Example

## Packages that you need to have:

### Set Up Sequelize
Ensure that Sequelize and the PostgreSQL driver are installed.

**npm install sequelize pg pg-hstore**


![Screenshot 2025-02-05 at 5 16 42 PM](https://github.com/user-attachments/assets/f8d25382-a428-4c81-9c40-5aa2e441d0c7)

### Install TypeScript and Necessary Typings
If not installed already, add TS and Node.js types, and Sequelize types into the project.

**npm install typescript @types/node @types/express @types/bcrypt @types/sequelize**

You might also need to initialize TS in your project

**npx tsc --init**

### Secure the Passwords

Never EVER store passwords as plain text. Use a library like bcrypt to hash passwords before storing them.

**npm install bcrypt**


### Integration
Ensure your Node.js server is set up to handle routes and integrate this with your frontend. Use middleware like body-parser to parse JSON requests.





