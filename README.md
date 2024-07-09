# Create React App Lab

## A. Scenario

When starting to build a new React application, `Create Vite` is (at the time of writing this lab) the best way to get started. It bundles an entire toolchain into some handy, preconfigured, scripts that can be used directly from yarn or npm.

## B. What you will be working on in this lab

In this lab you'll be testing the `create-vite` library.

## C. Lab instructions

### Create a new SPA

All you have to do to create a new SPA with React is to launch the `create vite` script that is available through `npm`.
Since you only have to do this once per project, there is no need to download the script - just run `npm create vite@latest my-spa --template react-ts` and you will have a new React project called `my-spa`.

#### Exercise 1

Create a new React application from your current directory using the `create vite` script.
Open the new project in VS Code and examine what has been created. Look into both the source files and the configuration inside `package.json`.

Run the command `npm run dev`. What happens?

Then take an extra moment and analyze the output of `npm run build`. What is the purpose of this script and what is the difference from how we run the application with `npm run dev`?

#### Exercise 2

Check out the [Vite docs](https://vitejs.dev/guide/) to learn more about Vite and what you can do. Try out `run npx vite --help` in your project to see a full list of available CLI options. 
