# A portfolio starting point for Sanity Studio

This Studio Starter comes with Schemas for projects, blog content, gallery support, collaborators, and more. 


## Running the Studio from the Starter

When you use the 1-click installer, you'll get only what you need for the Studio itself. After you clone it locally, you can run the following commands to get up and running.

```sh
cd studio
sanity install
sanity start
```


## Running the template (for developing the Starter)

This repository isn't your typical Sanity Studio. This is a template to create a [1-click Starter](https://sanity.io/create). 

To run this locally, you'll want to rename `~/studio/.env-template` to `~/studio/.env.development` and modify the values for a project with your test data.

From there, you'll be able to run `sanity start` inside the Studio like normal.

If you want to create a frontend for the Starter, use [sanity.io/create](https://create.sanity.io) to create a new project with test data, and then create the frontend as a sibling to the `/studio` directory.

You'll then modify the `/.sanity-template/manifest.json` to describe the new site for Netlify following [the official guide](https://www.sanity.io/guides/creating-a-1-click-sanity-starter-project#creating-metadata-and-deployment-information-in-sanity-templatejson-977da85223dc).
