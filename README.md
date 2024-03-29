# Gastro Template 

A starter to create manage a storefront with [Gatsby](https://gatsbyjs.org/), [Stripe](https://stripe.com/), & [Netlify Functions](https://www.netlify.com/docs/functions/); includes cart, checkout, admin, and live data. 

## Screenshot 

<img src="assets/Screenshot.png" width="60%"></img>

## Features

- Create and manage menus through the admin interface
- Serverless functions that interact with Stripe API
- Checkout powered by Stripe
- Dynamically update menus with new changes made to restaurant programs
- Statically generated menus through Stripe's products API

## 🚀 Getting Started

1.  **Create a Restaurant site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ````shell
    # create a new Gatsby site using this template
    gatsby new the-gluttonous-anorexic https://github.com/CaninoDev/gastro-template
    # Navigate into your new site’s directory and start it up.
    	cd the-gluttonous-anorexic
    	```

    ````

1.  :nut_and_bolt: **Setup**

    1.  **Setup Stripe.**

    This starter has an admin interface to manage your inventory, but the Stripe integration does not handle an empty account well. Before starting your site, you should create at least one product and price in Stripe.

    2. **Configure API keys.**

    Rename `.env.example` to `.env` and populate with Stripe API test keys. **Don't commit this file to a public repository!**

    3. **Install Development Servers.**

    You will need to install and configure [Netlify CLI](https://docs.netlify.com/cli/get-started/):

    ```shell
    # npm
    npm install netlify-cli -g
    # yarn
    yarn global add netlify-cli
    ```

1.  **Start Development Servers.**

    To start development servers for Gatsby & [Netlify Functions](https://github.com/netlify/netlify-lambda#usage):

    ```shell
    netlify dev
    ```

1.  **Start Development**

    This template spins out boilerplate code to integrate Gatsby and Stripe for the back-end. Everything else is left for the developer.

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `the-gluttonous-anorexic` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

    The source files for [Netlify Functions](https://www.netlify.com/docs/functions/) are located at `/src/functions`.

## :mag: What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── .env.sample
    ├── .gitignore
    ├── .prettierrc
    ├── node_modules/
    ├── src/
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── netlify.toml
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`.env.sample`**: This file contains Stripe API test keys and other environment variables for the project.

2.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

3.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

4.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

5.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

6.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extensin of default Gatsby settings affecting the browser.

7.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

8.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

9.  **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.org/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

10. **`LICENSE`**: This Gatsby starter is licensed under the 0BSD license. This means that you can see this file as a placeholder and replace it with your own license.

11. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

12. **`README.md`**: A text file containing useful reference information about your project.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

## 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-default)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/gatsbyjs/gatsby-starter-default)
o

