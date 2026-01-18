# afloof.dev

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

## Project Structure

Here's a rough overview of the different directories:

* `images/`: Assets copied as-is to the final site.
* `structure/`: Contains `.json` files, each describing a single page and its contents.
* `md_files/`: `markdown` content files, used by the `.json` files above.
* `metadata/`: Contains etcetera files needed on the final site, copied as-is.
