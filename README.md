# afloof.dev

![Website](https://img.shields.io/website?url=https%3A%2F%2Fafloof.dev)
![PingPong uptime (last 30 days)](https://img.shields.io/pingpong/uptime/sp_12c35d6d41dc40849b3c01656bd5f9cf)

A site I made to document different projects I'm working on,
like video games, drawings and music composition.

Take a look: [https://afloof.dev/](https://afloof.dev/)

## How is it made

This project started as a basic bash script, which slowly
grew. Now it is using markdown to describe different
parts of a site, and json to link those parts together.

## Compile

To compile, there's only two dependencies.

* `markdown`: Used to parse Markdown text to HTML
* `jq`: Used to parse json files.

After installing those, simply run the following:

    make

The site will now be ready in the `_site` directory`.
