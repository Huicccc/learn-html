## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
When the user submits the form, the data will be sent to the /login route on the server hosted at http://localhost:3000
2. What is the purpose of the _method_ attribute in the _form_ tag?
Specify the HTTP method that should be used when submitting the form data. 
In the server code, the route is defined to handle GET requests using app.get('/login', ...).
3. What is the purpose of the _name_ attribute in the _input_ tag?
This name is used as the key when the form data is sent to the server. 
In the server code, req.query.username is used to access the values of input field.
4. What is the purpose of the _type_ attribute in the _input_ tag?
Specify the type of input control that should be rendered.
5. What is the purpose of the _label_ tag?
The description for an input element.
6. What is the purpose of the _required_ attribute? 
Input field must be filled out by the user.

