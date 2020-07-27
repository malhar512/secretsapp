# Authentication with Google and facebook using passportjs for Secrets app
## Using this anyone can share their secrets without revealing their names .

Various Frameworks used in this project :
  **1.Front-end**
  -HTML5
  -CSS3
  -BootStrap4
  -JavaScript

  **Back-end**
  -Nodejs
  -Expressjs
  -MongoDB(mongoose)
  -Passportjs(npm library)
    
        In this project, the main aim is to authenticate user with Google account or Facebook account, which is mainly done with passport.js which is npm package. Once a user registers to our website his Google Id/Facebook Id is received and saved in our MongoDB database and hence Users' data is safely saved in our database. After registering user can later login through registered account.Now since information is secured user can share secrets anonymously and safely.
        Styling of website is mainly done using HTML, CSS, Bootstrap and Javascript, While Back End is runs on Nodejs, ExpressJs and Mongoose (Library for MongoDB) running on AWS.
    The Authentication is done using passport-google-OAuth20 strategy for Google and passport-facebook for Facebook in Passportjs

If you want to run this project on your System, here are steps to do so:
  1. Clone this app and download the source code.
  2. Use `npm install` in command prompt at location of your folder containing source code, to download npm packages.
  3. Check [Passportjs](http://www.passportjs.org/) for better understanding of Authentication Process.
  4. Create account on Google for developers and facebook for developers to get API keys and Secrets.Be careful to save them securely as they contain sensative information.
  5. Connect application to MongoDB either locally or on MongoDB Atlas to save information on database.
  6. Use `node app.js` in command prompt to run code on localhost:3000
  
