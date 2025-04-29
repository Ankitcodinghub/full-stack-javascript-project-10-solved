# full-stack-javascript-project-10-solved
**TO GET THIS SOLUTION VISIT:** [FULL_STACK_JAVASCRIPT Project 10 Solved](https://www.ankitcodinghub.com/product/full_stack_javascript-project-instructions-full-stack-app-with-react-and-a-rest-api-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116357&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FULL_STACK_JAVASCRIPT Project 10 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Project Instructions: Full Stack App with React and a REST API

Github

• Create a new repo for this project.

• Create a .gitignore and use it to make sure your node_modules folder is not stored in or tracked by your repo.

• Create a README.md file for your repo that explains what the project is and anything your user or fellow developers might need to know to use the project.

Understand what you are working with

• Have a basic understanding of React, JSX, Create React App, React Router, React Context API, React authentication, and working with APIs.

Download the project files:

• The markup folder contains a collection of HTML files that will show you how each page in the app should be structured.

• The styles/global.css file contains all the styles you will need for this project, but you are encouraged to experiment with things like colors, background colors, and fonts.

• The mockups folder contains a collection of PNG image files showing you how each page should look with the provided HTML and CSS applied.

Create your React project

• Use the create-react-app tool to set up and create your React project in a folder named client.

o To do this, run the command npx create-react-app client from the root of your repo.

NOTE: npx is not a typo — it’s a package runner tool that comes with npm 5.2+.

Set up your REST API

• Add a folder named api to the root of your repo.

• Copy the REST API Express application from your unit 9 project into the api folder.

Add CORS support to your REST API

• When developing your React application, you’ll be using the create-react-app development server, which will host your application (by default) at http://localhost:3000/. Your REST API, will

be hosted separately from your React application at http://localhost:5000/. While both the React and REST API applications will be using the same hostname, localhost, their port numbers differ, so the browser will treat them as separate origins or domains.

• To successfully make a request from the React application’s domain to the REST API’s domain, you’ll need to update your REST API application to support cross-origin resource sharing or CORS (see MDN web docs: https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS for more information about CORS).

o Add a middleware function to set the appropriate headers to support CORS.

o Alternatively, you can install and configure the cors npm package (https://www.npmjs.com/package/cors).

Test calling your REST API from your React application

• Before going any further, let’s ensure that your React and REST API applications are setup correctly and you can successfully call your REST API from your React application.

• Update the React App component (src/App.js file) to call the REST API to get a list of courses and render the results.

o We’re just confirming the setup of the applications, so just render the list of course titles using some simple markup (e.g. an unordered list or set of divs).

• Open a terminal or command window and start your REST API application.

o Browse to the api folder and run the command npm start.

o Once you’ve started the REST API application, you can typically just leave the app running in the background.

• Open another terminal or command window and start your React application.

o Browse to the client folder and run the command npm start.

o The create-react-app development server should start and open your application into your default browser. If the development server started but it didn’t open in the browser, try manually browsing to it at http://localhost:3000/.

Build your app components

• Use the provided HTML files (see the markup folder in the project files download) as a guide while you create the components for this project.

• Use the App component (src/App.js file) that was generated by the create-react-app tool as your main container component.

• Create the following stateful class components:

o Courses – This component provides the “Courses” screen by retrieving the list of courses from the REST API’s /api/courses route and rendering a list of courses. Each course needs to link to its respective “Course Detail” screen. This component also renders a link to the “Create Course” screen.

o CourseDetail – This component provides the “Course Detail” screen by retrieving the detail for a course from the REST API’s /api/courses/:id route and rendering the course. The component also renders a “Delete Course” button that when clicked should send a

DELETE request to the REST API’s /api/courses/:id route in order to delete a course. This

component also renders an “Update Course” button for navigating to the “Update Course” screen.

o UserSignIn – This component provides the “Sign In” screen by rendering a form that allows a user to sign using their existing account information. The component also renders a “Sign In” button that when clicked signs in the user and a “Cancel” button that returns the user to the default route (i.e. the list of courses).

o UserSignUp – This component provides the “Sign Up” screen by rendering a form that allows a user to sign up by creating a new account. The component also renders a “Sign Up” button that when clicked sends a POST request to the REST API’s /api/users route and signs in the user. This component also renders a “Cancel” button that returns the user to the default route (i.e. the list of courses).

o CreateCourse – This component provides the “Create Course” screen by rendering a form that allows a user to create a new course. The component also renders a “Create

Course” button that when clicked sends a POST request to the REST

API’s /api/courses route. This component also renders a “Cancel” button that returns the user to the default route (i.e. the list of courses).

o UpdateCourse – This component provides the “Update Course” screen by rendering a

form that allows a user to update one of their existing courses. The component also renders an “Update Course” button that when clicked sends a PUT request to the REST API’s /api/courses/:id route. This component also renders a “Cancel” button that returns the user to the “Course Detail” screen.

• Create the following stateless functional components:

o Header- Displays the top menu bar for the application and includes buttons for signing in and signing up (if there’s not an authenticated user) or the user’s first and last name and a button for signing out (if there’s an authenticated user).

o UserSignOut – This component is a bit of an oddball as it doesn’t render any visual elements. Instead, it signs out the authenticated user and redirects the user to the default route (i.e. the list of courses).

Pro Tip: Resist the temptation to keep and manage the courses data as global state in the App component. Instead, allow the Courses and CourseDetail components to retrieve their data from the REST API when those components are mounted. Using this approach simplifies the management of the courses data and ensures that the data won’t get out of sync with the REST API’s persisted data.

Set up your routes

• Install React Router and set up your &lt;Route&gt; and &lt;Link&gt; or &lt;NavLink&gt; components.

• Clicking a link should navigate the user to the correct route, displaying the appropriate info.

• The current route should be reflected in the URL.

• Your app should include the following routes (listed in the format path – component):

o / – Courses

o /courses/create – CreateCourse o /courses/:id/update – UpdateCourse o /courses/:id – CourseDetail o /signin – UserSignIn

o /signup – UserSignUp

o /signout – UserSignOut

Add support for user authentication

• To prepare for implementing user authentication (i.e. user sign in and sign out), determine where you’ll manage your application’s global state.

o One option, is to keep your global state in your App component. Using this approach, the authenticated user and the user sign in and sign out actions (i.e. methods) are made available throughout your application, by using props to pass references down through your component tree.

o Another option, is to manage your global state using the React Context API. Using this approach, the authenticated user and the user sign in and sign out actions (i.e. methods) are defined using a Context API &lt;Provider&gt; component and made available throughout your application using Context API &lt;Consumer&gt; components.

• Create your signIn() method:

o Your signIn() method should define emailAddress and password parameters.

o To authenticate the user, make a request to the REST API’s /users endpoint, using the emailAddress and password parameter values to set an Authorization header on the request using the Basic Authentication scheme.

o If the request to the REST API succeeds (i.e. the server returns an “200 OK” HTTP status code), then you’ll know that the supplied user credentials are valid. If the server returns a “401 Unauthorized” HTTP status code, then the supplied user credentials are invalid.

o After validating the user’s credentials, persist the returned user record and the user’s password in the global state. Doing this will allow you to create and set the appropriate Authorization header on future REST API requests that require authentication.

• Create your signOut() method:

o The signOut() method should remove the authenticated user and password from the global state.

Configure your protected routes

• Define a higher-order component (HOC) named PrivateRoute for configuring protected routes (i.e. routes that require authentication).

o Use a stateless functional component to wrap an instance of the &lt;Route&gt; component. o Use the &lt;Route&gt; component’s render property to define a function that renders the component associated with the private route if there’s an authenticated user or redirects the user to the /signin route if there’s not an authenticated user. o For an example of how this is done, see: https://reacttraining.com/reactrouter/web/example/auth-workflow in the React Router documentation.

• Update the following routes to use the PrivateRoute component

o /courses/create

o /courses/:id/update

Restrict access to updating and deleting courses

• On the “Course Detail” screen, add rendering logic so that the “Update Course” and “Delete Course” buttons only display if:

o There’s an authenticated user.

o And the authenticated user’s ID matches that of the user who owns the course.

Display validation errors

• Update the “Sign Up”, “Create Course”, and “Update Course” screens to display validation errors returned from the REST API.

• See the create-course.html file in the markup project files folder.

Add support for rending markdown formatted text

• Use npm to install the react-markdown package (see https://www.npmjs.com/package/reactmarkdown for more information).

• On the “Course Detail” screen, use the &lt;ReactMarkdown&gt; component to render the course description and materialsNeeded properties as markdown formatted text.

Add HTML and CSS

• Use the HTML files contained within the markup project files folder as a guide while you create the components for this project.

• Use the CSS contained within the global.css file in the styles project files folder for your application’s styles.

o Free free to experiment with modifying the colors, background colors, or fonts in order to personalize your application.

Add code comments!

Cross-Browser consistency:

• Google Chrome has become the default development browser for most developers. With such a selection of browsers for users to choose from, it’s a good idea to get in the habit of testing your projects in all modern browsers.

EXTRA CREDIT

Display user friendly messages

• A well-designed application will display user-friendly messages when things go wrong. For example, when a requested page can’t be found.

• Create the following stateless functional components:

o NotFound – Display a message letting the user know that the requested page can’t be found.

o Forbidden – Displays a message letting the user know that they can’t access the requested page.

o UnhandledError – Display a message letting the user know that an unexpected error has occurred.

• Add the following routes (listed in the format path – component):

o /notfound – NotFound o /forbidden – Forbidden

o /error – UnhandledError

• Update the CourseDetail and UpdateCourse components to redirect users to the /notfound path if the requested course isn’t returned from the REST API.

• Update your React Router configuration so that if a route isn’t matched the NotFound component will be rendered.

• Update the UpdateCourse component to redirect users to the /forbidden path if the requested course isn’t owned by the authenticated user.

• Throughout your application, redirect users to the /error path when requests to the REST API return a “500 Internal Server Error” HTTP status code.

Persist user credentials

• After successfully authenticating a user, persist their credentials using an HTTP cookie or local storage so that the user’s authenticated state is maintained even if the application is reloaded or loaded into a new browser tab.

Redirecting the user after successfully signing in

• After a user successfully signs in, redirect them back to the previous screen (whatever that happens to be).

o For example, if a user attempts to view the “Create Course” screen before they’ve signed in, they’ll be redirected to the “Sign In” screen. After the user has successfully signed in, redirect them to the “Create Course” screen.
