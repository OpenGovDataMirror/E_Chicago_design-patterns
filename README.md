# CDS Design Library
This repository serves as a library for the City of Chicago's colors, patterns, logos, and all other assets. 
It is meant to serve as a guide for city web products, and is open to contribution and discussion. This project
is completely open source and in the public domain under the [CC0 1.0 License](https://creativecommons.org/publicdomain/zero/1.0/).
Any municipality or other organization is free to use, modify, and publish content using designs created for the Design Library. In its current iteration, the CDS takes heavily from the federal government's US Web Design System, and is a direct fork of that project.


## Fractal
Fractal is used to publish the atomic design elements of the Chiago Design System. You will need to install the CDS Fractal fork in order to edit and preview your changes to the CDS pattern library. [Go here](https://fractal.build/guide) for more information on Fractal and [here](http://bradfrost.com/blog/post/atomic-web-design/) for more information on atomic design.

1. If you haven't already, install npm. npm is a package manager for Node based projects. Below is a link to find the install method that coincides with your operating system:
    * Node v4.2.3+, [Installation guides](https://nodejs.org/en/download/)
1. Navigate to the design-library directory
2. Run
```
npm install
```
3.  Run npm start to make sure it's up and running
```
npm start
```
4. Make changes to the components in the 'src' folder
5. Run 
```
npm install
```
6. Install [fractal](https://fractal.build/guide/cli)
```
npm i -g @frctl/fractal
``` 
7. Run fractal build to generate the static site
```
fractal build
``` 
8. Open the docs folder static site to make sure it generated correctly
9. Sync with the repo
10. Make a pull request

For more detailed information on USWDS patterns and their fractal setup, please look at 
[their Github repository](https://github.com/uswds/uswds).
