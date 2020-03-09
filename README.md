# Team Profile Generator

![photo of a team of people](https://user-images.githubusercontent.com/55456375/76181868-4c31cc80-6188-11ea-9e82-6dcfa88ad5b7.png)

One of the most important aspects of programming is writing code that is readable, reliable, and maintainable. Oftentimes, how we design our code is just as important as the code itself. In this homework assignment, your challenge is to build a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person. Since testing is a key piece in making code maintainable, you will also be ensuring that all unit tests pass.

Instructions
You will build a software engineering team generator command line application. The application will prompt the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. This assignment must also pass all unit tests. When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user. Following the common templates for user stories, we can frame this challenge as follows:
As a manager
I want to generate a webpage that displays my team's basic info
so that I have quick access to emails and GitHub profiles
How do you deliver this? Here are some guidelines:


Use the Inquirer npm package to prompt the user for their email, id, and specific information based on their role with the company. For instance, an intern may provide their school, whereas an engineer may provide their GitHub username.


Your app will run as a Node CLI to gather information about each employee.


Below is an example of what your application may look like. Remember, the styling is completely up to you so try to make it unique.




In the Develop folder, there is a package.json, so make sure to npm install.
The dependencies are, jest for running the provided tests, and inquirer for collecting input from the user.
There are also unit tests to help you build the classes necessary.
It is recommended that you follow this workflow:

Run tests
Create or update classes to pass a single test case
Repeat

🎗 Remember, you can run the tests at any time with npm run test
It is recommended that you start with a directory structure that looks like this:
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
