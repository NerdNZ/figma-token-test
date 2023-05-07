# Figma Design Tokens & Style Dictionary

## How does this work?

As designers at a large company, we need a single source of truth for our designs.
We can do this by pulling in our styles from Figma to a repository (doesn't have to be github, could just sit inside each of our applications).
Figma design tokens are JSON format and to read them with our code we need to convert it to CSS. We do this with Style Dictionary.

## How do I run this?

git clone 

cd figma-token-test

npm install

npm run build

### What's the input / output?

The input comes directly from Figma. It lands in the "tokens.json" file in the root of the directory.

https://www.figma.com/file/o8H8bRC1bn0grapxBSHXzZ/V1?node-id=0%3A1&t=83OuPxx3xhJeIafz-1

We use config.json to create a style dictionary framework which defines the output

The output is held within the build folder.