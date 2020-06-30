# Read 27 ~ React Testing and Deployment
> By Abdallah obaid

**NAME**     | **URL**
------------ | -------------
Home         | [Home](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/).
 Prep        | [Prep: Engineering Topics](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/Prep).
 Read 01     | [Node Ecosystem, TDD, CI/CD](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-01).
 Read 02     | [Classes, Inheritance, Functional](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-02).
 Read 03     | [Data Modeling & NoSQL Databases](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-03).
 Read 04     | [Advanced Mongo/Mongoose](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-04).
 Read 05     | [Linked Lists](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-05).
 Read 06     | [HTTP and REST](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-06).
 Read 07     | [Express](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-07).
 Read 08     | [Express Routing & Connected API](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-08).
 Read 09     | [API Server](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-09).
 Read 10     | [Stacks and Queues](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-10).
 Read 11     | [Authentication](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-11).
 Read 12     | [OAuth](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-12).
 Read 13     | [Bearer Authorization](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-13).
 Read 14     | [Access Control (ACL)](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-14).
 Read 15     | [Trees](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-15).
 Read 16     | [Event Driven Applications](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-16).
 Read 17     | [TCP Servers](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-17). 
 Read 18     | [Socket.io](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-18).
 Read 19     | [Message Queues](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-19).
 Read 26     | [Component Based UI](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-26). 
 Read 27     | [React Testing and Deployment](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-27). 

----------------------------------
# React Testing 
----------------------------------

 ## Snapshots :
  * Its make a shot for the exact rendered tree dom and use it to be compared with later versions.

 ## Render Testing:
  * Using **react-test-renderer** module
  * Similar to snapshots, but allows for jQuery-like inspection of the virtual DOM tree.

 ## Shallow Testing :
  * Allows us to test the parent component without testing their children.

 ## Mounting:
  * Allows us to test the parent component and also testing their children. 
 
----------------------------------
# React Deployment
----------------------------------
 > **React, remember is an index.html file that uses Javascript to render components in the browser. The node server is only there to aid in your development.**
 > `npm run build` output a **static website** containing no more than the `index.html`, `.js` and `.css` files required to open your app. 

 ## Deploying to GitHub Pages:
  1. Enable GitHub Pages on your domain, using the gh-pages branch
  2. Create a Personal Access Token in your GitHub account
  3. Add this token as a “Secret” called PERSONAL_TOKEN in the repository housing your react app
  4. Add the react workflow .yml file to your repository (in .github/workflows)

 ## Deploying to AWS (s3):
  1. Create a new Bucket
      * Storage containers for static assets
      * Essentially, these are “folders”
  2. Objects
      * These are the things in the buckets (your files)
      * Upload the contents of your React application build folder to your bucket
  3. Set up to serve websites
      * Properties Tab “Static Web Hosting” option

 ## Deploying to AWS Amplify:
  1. Create a new Amplify Workflow
  2. Point the workflow at your GitHub repository (master branch)
  3. Merge your code to master on GitHub
  4. That’s it … Amplify will monitor your repository for changes, pull, build, and deploy your React app automatically
  5. Eventually, there’s a usage charge for the service, depending on your traffic level
 ## Deploying to Netlify:
  1. Create a netlify.com account
  2. Create a new application
  3. Point the application at your GitHub repository (master branch)
  4. Merge your code to master on GitHub
  5. That’s it … Netlify will monitor your repository for changes, pull, build, and deploy your React app automatically

 ## Deploying to an “old school” host, such as godaddy.com:
  1. Create your account
  2. Open an FTP connection to your hosting company with a tool like Transmit or FileZilla
  3. Navigate to the web root folder
  4. Upload the contents of your react application’s build folder
 
 ![React](./Img/React.jpg)