# Portfolio Website

This repo contains my portfolio website written with [GatsbyJS](https://www.gatsbyjs.org/), integrated with content coming from [DatoCMS](https://www.datocms.com).



[Link to page](https://adrianberger.netlify.com/)


## Repo usage

First, install the dependencies of this project:

```
yarn install
```

Add an `.env` file containing the read-only API token of your DatoCMS site:

```
echo 'DATO_API_TOKEN=abc123' >> .env
```

Then, to run this website in development mode (with live-reload):

```
yarn develop
```

To build the final, production ready static website:

```
yarn build
```

The final result will be saved in the `public` directory.

This websites uses:

* [Yarn](https://yarnpkg.com/) as package manager;
* [GatsbyJS](https://github.com/gatsbyjs/gatsby) as website generator;
* [gatsby-source-datocms](https://github.com/datocms/gatsby-source-datocms) to integrate the website with DatoCMS.
