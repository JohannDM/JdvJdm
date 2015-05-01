# DeFrosted

This Git Repository will be used to collaborate on the DeFrosted project.

## Project time-line
- **3 May**: Indiegogo Launch 
- **10 May**: Planning finished
- **15 June**: End of Indiegogo run

### Coding Standard
Please follow Google coding standards throughot the implementation of this project.

We will be using http://usejsdoc.org/about-getting-started.html to generate documentation for our project. 
So remember to document your code.

### **Version Control** - git and npm
Both GitHub and npm will be used to collaborate and perform version control of this project. 

We ask that you periodically or after reaching some milestone publish a release (with incrementing version number e.g the first release will be v0.0.1 the second v0.0.2 and so on) 
see https://help.github.com/articles/creating-releases/ for more information.

We would like everyone to use the flowing template for the package.json file (modify as needed & enter relevant details)
```
{
  "private": true,
  "main": "mainFileName.js",
  "name": "ModuleName",
  "description": "Module description",
  "version": "0.0.1",
  "repository": {
    "type": "git",
    "url": "https://github.com/BuzzSpaceB/Module"
  },
  "bugs": {
    "url": "https://github.com/BuzzSpaceB/Module/issues"
  },
  "homepage": "https://github.com/BuzzSpaceB/Module",
  "contributors": [
    {
      "name": "Group Member One",
      "email": "group@member.com"
    },
    {
      "name": "Group Member Two",
      "email": "email@group.com"
    },
    {
      "name": "Group member n",
      "email": "n@email.com"
    }
  ],
  "dependencies": {
      "body-parser": "~1.12.0",
      "broadway": "^0.3.6",
      "cookie-parser": "~1.3.4",
      "debug": "~2.1.1",
      "ejs": "~2.3.1",
      "electrolyte": "0.0.6",
      "express": "~4.12.2",
      "handlebars": "^3.0.0",
      "jsreport": "^0.2.10",
      "ldapjs": "^0.7.1",
      "mongoose": "^3.8.25",
      "morgan": "~1.5.1",
      "node-aop": "^0.1.0",
      "node-cache": "^1.1.0",
      "nodemailer": "^1.3.2",
      "react": "^0.13.1",
      "react-bootstrap": "^0.17.0",
      "scribe-js": "^2.0.4",
      "serve-favicon": "~2.2.0"
    }
}

```