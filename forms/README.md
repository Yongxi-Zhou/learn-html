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
   It represents the request end point after clicking the submit button.

2. What is the purpose of the _method_ attribute in the _form_ tag?
   It represents the request method after clicking the submit button.

3. What is the purpose of the _name_ attribute in the _input_ tag?
   It's used to define the key in the url and the value is the input value.

4. What is the purpose of the _type_ attrbute in the _input_ tag?
   It's used to define the type of the input. It can be checkbox, text or password.

5. What is the purpose of the _label_ tag?
   It's used to bind the input with it.

6. What is the purpose of the _required_ attribute?
   That means this input shouldn't be empty when it's submitted.
