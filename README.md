                                                           Chapter 02 - Assignment - Igniting our App

**1) What is NPM?**

`       `In React we are using Bundlers (i.e. Parcel) and parcel is a package or a module and to handle this package we need a package manager. This package Manager is known as a NPM.

**2) What is `Parcel/Webpack`? Why do we need it?**

`      `Basically Both Parcel and Webpack is a Bundler. Parcel is **a Zero Configuration** web application. Parcel is a very fast & easy to learn.

We need Parcel Because,

1) Minify our code
1) Cleaning our code
1) Image optimization
1) HMR- Hot Module Replacement 
1) File Watcher Algorithm- C++
1) Caching While Development 
1) Port Number
1) Compatible with older version of browser
1) Consisting Hashing Algorithm

**3)  What is Parcel Cache?**

`          `The Parcel Cache Folder stores information about your projects, so when our parcel rebuilds, so it doesn’t have to re-parse and re-analysis everything from a Scratch. It is a key reason why parcel is fast in development mode. 

**4) Difference Between Dependencies & DevDependencies?** 

`         `Dependencies: Packages require for your application in Production. Ex: React, ReactDom.



`         `DevDependencies: Packages require for your local development & testing. Ex: Parcel.

**5)What is Hot Module Replacement?**

`        `HMR means whenever we add or remove module or you can say tags, HMR will runs that application without reloading the browser.

**6) List down your favorite 5 superpowers of parcel & describe any 3 of them in your words?**

- HMR- Hot module replacement is my favorite superpower in parcel because you don’t have to reload your browser after adding or removing some module, it will automatically run.
- Cleaning our code- We have a seen that whenever we written our code sometimes we have to write that is not needed but our understanding we write that (example- Console.log), after our project is done we forgot to remove that code which we don’t needed but our parcel is doing for us.
- Image Optimization- The heaviest object in an any file is image, sometimes we have to compress that image and doing this we lost our quality of that image. Parcel will automatically reduce size of our image without losing the quality of that image.
- HTTPS or DEV
- Caching While Development

**7) What is the difference between “package.json” & “package-lock.json”?**
**
`          `Package.json – It stores the basic information about our project which is necessary for us like Author, Project name, Description.

`          `Package-lock.json – It is a lockfile that holds the information on the dependencies or packages installed for our project, including their exact version numbers.

**8) What is npx?**

`         `NPX is basically to execute your NPM Package Manager (i.e. JavaScript Package). 

**9) What is BrowserLists?**

`         `BrowserLists means which browser our application should support. It will help to run our code in any browser.

**10) What is dist?**

`            `When we run a command (i.e. npm parcel index.html) it’s just create a development build for us and its hosted our server. Now if you want to make a production build we have to use build command. Parcel will build all the production file in the dist folder.

**11) What is tree shaking?**

`           `Tree shaking is used to remove the dead or unwanted code which is basically done by bundlers.

**12) What is .gitignore? what should we add or not add to it?**

`           `Gitignore file is a text file that tells git which files or folders to ignore it. We should add that file in our project that is autogenarated.

**13) What is a node module & should we push into git?**

`           `Node modules contains all the packages that we need in our project, like react, reactdom, minify. We should not push our node module into a git, because it can be auto generate later based on a package-lock.json.

