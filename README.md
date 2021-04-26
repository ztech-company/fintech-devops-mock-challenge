
# The Challenge

This project is intended to evaluate your knowledge with CI/CD using Azure DevOps.
It's a web application that is constructed using node.js, dotnet core and JavaScript and CSS files.
A example script to build and generate a package is illustrate in the file build.sh

Create a Azure Pipeline to abstract the Script using tasks to:

- Use a Ubuntu Agent
- Install the Node.js packages defined in package.json
- Convert Sass (.scss) files to CSS (.css)
- To minify JavaScript and CSS files
- Print the build number and date info in wwwroot directory
- Install the dependêncies using dotnet
- Build the project using dotnet
- Publish the package as a .zip using dotnet

Fork this repository, create your Azure Pipeline and send us the link for evaluation.
