# Unit 3 Solo Projects

## Examples of past projects
Note that these projects were done in groups, while we are doing ours solo.

https://gawdiseattle.gitbook.io/wdi/11-projects/past-projects/project3

## Project Requirements
- Two repos in your own personal github, one containing your frontend and one containing your backend.
- A backend express server that persists data to a database
  - At least 2 tables in your database
  - A sequelize model for each of your database tables
  - At least one association (1-t-m or m-t-m) among your sequelize models
  - Routes that allow CRUD operations on your database tables
  - Backend support for user authentication flow, including password hashing (using bcrypt) and userId encryption (using jwt)
- A frontend react app that interacts with your own express backend
  - User authentication flow (creating an account, logging in, logging out) that uses both localStorage and top-level state
  - Page transitions that the user can navigate easily
  - At least one component that is repeated, either via a loop or component reuse
- Your app either interacts with a 3rd party API, or has sufficiently complex CRUD on your own data (as determined by your pod leader)
- Deploy both the frontend and the backend using Heroku (there will be a deployment jam!)
- A `README.md` containing sections described below

## README requirements / pitch requirements
Your pitch is due Thursday 4/29. Make two repos for this project in your own personal github, one for the frontend and one for the backend. Make a `README.md` in either one; this README will contain your pitch. Your README should contain:

1. Title of the project (biggest header in the document)
1. Overview: summarize the goals of your app, and describe the problem your app is built to solve.
1. Wireframes: Use a tool like https://awwapp.com/, https://www.mockflow.com/, or good ol zoom whiteboard to create wireframes for your project. Take a screenshot and link to the images in your readme. Your wireframes should walk the reader through the screen states, and should include short descriptions of each screen. It's a good idea to give your wireframes labels (like 1, 2, 3 etc), and to indicate which screens transitions to which other screens.
1. User stories: a series of statements in the form of "When I {do X}, {Y happens}." These statements should encompass the whole functionality of your app.
1. Routes inventory: list all the routes you plan to have in your backend. Include the http verb, the path, and a brief summary of what the route does. (To represent this nicely in markdown, you might want to look up how to make a table in a markdown file!)
1. Database ERD: diagram all your tables, columns, and associations. You can use a tool like this https://app.dbdesigner.net/designer/schema/new, and screencap the image.
1. Frontend components tree: Diagram out your component hierarchy, indicating which components are parents/children of which others. Indicate which components hold which pieces of state, and which props are passed to each child.
1. MVP checklist: A list of all the functionalities that will constitute the bare minimum version of your app. Note that this list should be sized so that you can complete it by ~Monday, leaving Tuesday to tackle stretch goals.
1. Stretch goals: A list of awesome bonus goals you will work on after completing your MVP.


## Project Feedback + Evaluation

* __Project Workflow__: Did you spend an adequate amount of time on the planning process? Did you use source control as expected? Are your commit messages clear? Do you have a readme file?

* __Technical Requirements__: Did you deliver a project that met all the technical requirements? Given what the class has covered so far, did you build something that was reasonably complex?

* __Creativity__: Did you added a personal spin or creative element into your project submission? Did you deliver something of value to the end user (not just a login button and an index page)?

* __Code Quality__: Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code as your instructors as we have in class?

* __Problem Solving__: Are you able to defend why you implemented your solution in a certain way? Can you demonstrated that you thought through alternative implementations? _(Note that this part of your feedback evaluation will take place during your one-on-one code review with your instructors, after you've completed the project.)_

* __Total__: Your instructors will give you a total score on your project between:

| Score | Expectations | Evaluation Criteria |
| ----- | ------------ | ------------------ |
| **3** | _Exceeds expectations_ | **Solid MVP + Stretch Goals**
| **2** | _Meets expectations_ | **Solid MVP -- meets all technical requirements** 
| **1** | _Does not meet expectations._ | **No MVP -- missed some technical requirements**
| **0** | _Incomplete._ | **Not Passing -- missed most or all technical requirments and MVP**
