# the locallibrary website

Tutorial "Local Library" website written in Node/Express.

For more information see the associated [MDN tutorial home page](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website).

## Getting Started

1. Install Nodejs

2. accept the assignment via the invitation link - https://classroom.github.com/a/j_Vbz8QI

3. clone it to your local PC

4. open the clone folder in VS CODE

   make sure the one your open in VS is the one you just clone. there should be two files, a README and gitignore file

5. In VS CODE click on terminal and new terminal

6. Within the terminal type the following and hit enter

   ```shell
   npm init
   ```

   Use the npm init command to create a package.json file for your application. This command prompts you for a number of things, including the name and version of your application and the name of the initial entry point file (by default this is index.js). For now, just accept the defaults:

   If you open the package.json file you will see the defaults that you accepted

7. Installing the Express Application Generator

   ```shell
   npm install express-generator -g
   ```

   The [Express Application Generator](https://expressjs.com/en/starter/generator.html) tool generates an Express application "skeleton". Install the generator using NPM as shown above

8. Installing the Express within this folder and template engine should be pug

   ```shell
   express . --view=pug
   ```

9. 