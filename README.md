# WebCM

WebCM is a proxy server implementation of a [Components Manager (CM)](https://managedcomponents.dev/getting-started/components-manager). It works independently from your existing HTTP server. By proxying your server, it can add endpoints, execute server-side code, manipulate responses and more. These capabilities allow for a very performant way to load Managed Components.

## Installation

To run WebCM you need to have Node version >= 18. You can then install all dependencies with `npm i`.

## Usage

1. Edit [config.json](tests/demo_config.json) to your preferences. Make sure to adjust the `target` key to point to your webserver.
2. Run `npm run dev`

## Execute

Run `npx webcm --c=tests/demo_config.json --mc=./components`

## Read more

- See [managedcomponents.dev](https://managedcomponents.dev) for more information about Managed Components and how they work
