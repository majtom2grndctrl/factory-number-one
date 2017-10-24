# Factory Number One (Centennial)

[![CircleCI Build Status](https://circleci.com/gh/18F/web-design-standards/tree/develop.svg?style=shield)](https://circleci.com/gh/18F/web-design-standards/tree/develop) [![Test Coverage](https://codeclimate.com/github/18F/web-design-standards/badges/coverage.svg)](https://codeclimate.com/github/18F/web-design-standards/coverage)

This is the (eventual) successor to Factory Number One, an open-source design system for City of Bloomington websites & applications. It's heavily influenced by the the [U.S. Web Design Standards](https://standards.usa.gov) 

This repository will house both the core components and documentation (for now.) 

## U.S. Web Design Standards (USWDS)

The [U.S. Web Design Standards](https://playbook.cio.gov/designstandards) is a library of open source UI components and a visual style guide for U.S. federal government websites.

These tools follow industry-standard web accessibility guidelines and reuse the best practices of existing style libraries and modern web design. Created and maintained by [U.S. Digital Service](https://www.whitehouse.gov/digital/united-states-digital-service) and [18F](https://18f.gsa.gov) designers and developers, the Web Design Standards are designed to support government product teams in creating beautiful and easy-to-use online experiences for the American people. Learn more about this project in their announcement [blog post](https://18f.gsa.gov/2015/09/28/web-design-standards/).

Design files of all the assets included on this site are available for download here: [https://standards.usa.gov/](https://standards.usa.gov/).


## About the starter
The starter folder is comprised of a static HTML template and a copy of the USWDS in CSS form. It's meant for testing purposes. 

## Setup

- Visual Studio Code (https://code.visualstudio.com/)
   - Live Server Extension
   - Live Sass Compiler

### Install using npm

`npm` is a package manager for Node based projects. The U.S. Web Design Standards maintains a [`uswds` package](https://www.npmjs.com/package/uswds) for you to utilize both the pre-compiled and compiled files on your project.

1. Install `Node/npm`. Below is a link to find the install method that coincides with your operating system:

  - Node v4.2.3+, [Installation guides](https://nodejs.org/en/download/)

2. Make sure you have installed it correctly:

  ```shell
  npm -v
  3.10.8 # This line may vary depending on what version of Node you've installed.
  ```

3. Create a `package.json` file. You can do this manually, but an easier method is to use the `npm init` command. This command will prompt you with a few questions to create your `package.json` file.

4. Add `uswds` to your project’s `package.json`:

  ```shell
  npm install --save uswds
  ```

The `uswds` module is now installed as a dependency. You can use the un-compiled files found in the `src/` or the compiled files in the `dist/` directory.

```
node_modules/uswds/
├── dist/
│   ├── css/
│   ├── fonts/
│   ├── html/
│   ├── img/
│   ├── js/
└── src/
    ├── fonts/
    ├── img/
    ├── js/
    ├── stylesheets/
    └── templates/
```

## About the name

2018 marks 150 years of existence for Monroe County & the City of Bloomington. Sesqicentennial seemed a bit long to say, so instead, we went with "Centennial" to differentiate this successor branch of Factory Number One.

Factory Number One is named after the Showers Brothers Furniture Company Factory Number 1. In the 1920s, the facility was arguably the largest furniture factory in the world, leveraging convenient access to the railroads to ship its dressers to retailers in large quantities. After World War II, the industry saw a shift from shipping by train, to shipping by truck, but the company didn't adapt to these changes in the market. The company closed its doors in 1958. Most of the facility was lost to a fire in 1969. One of the few buildings to survive was Factory Number 1. As of 2016, the building houses Bloomington, Indiana's City Hall, Monroe County offices, and office space for private companies.



