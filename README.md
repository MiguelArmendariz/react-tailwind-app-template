# react-tailwind-app-template
This project is a basic template for a react application using webpack, and
YARN as package manager.

## Content
* Webpack configuration for local and prebuild.
* Public folder like create-react-app.
* Src folder without file structuring.
* Babel configuration to work with react.
* Eslint with basic configuration **using Wesbos**
* The template works with both css and scss, but is highly recommended to use tailwind.
* MIT license.

#### Important Notes

When you run yarn first and start the project you should see some headers but **without** styles,
they should look identical.

**THIS NEEDS NODE 12.13.0**

#### Recommendations

I personally like to use **yarn-check** package because it offers a way to visualize which package to update and it highlights
if the package update is a patch, minor update, potentially breaker, etc.

You can use the command **yarn-check -u** to see it this way and **select only** the packages you want to update.

Feel free to contact me if you have suggestions/requests.
