# Organize the visual components of your project with Storybook

Storybook is a library that works as a sandbox where we as developers can document all the components of our app. So it will be easier to know what components we have, what actions they do, the colors they use, etc... Using storybooks we can have a library of our components and we can interact directly with them. So, we don't need to go to the code in our project to understand how our components works.

## Getting started

Incorporate storybook to a project is very easy. Whether we have a project that already exists or if we are starting from zero.

## Requirements

Node.JS and NPM are required, so after install this we can start.

## Installing storybook

Execute the follow instruction in the terminal to get storybook inside the folder of your project

`npx sb init`

In case you are not working in a project you need to install react

`npm i react react-dom`

Once installed you can start storybook with the follow command

`npm run storybook`

This will open a window on the web browser at address localhost:6006

Exploring this interface, we have in the left a panel with the components by default. We also have a canvas to explore and test the component we are at. Also we have a Doc tab, to see the documentation, where as a developer we can find useful information about implementation and uses of the component.

Creating button with emoji
Now we are moving to our code editor to add another button story, which implements an emoji.

The project is conformed fo a stories folder, among others. Exploring the Button.js file we have the following code

We can see that it is bringing react and proptypes libraries and some styles. It creates a button with some props and returning a button. It also use proptypes to describe the props, and add some default props just in case.

Now that we understand the Button,lets edit it to create a story that implements an emoji

So, we just added a prop named emoji and implemented below label, we also add its proptypes.

Now let's create a story for the emoji in the Button.stories.js file, it is just export a const with the name of the story and then add the args label an emoji as we see in the next image.

Let's see the result in the storybook page

And that's all! we just created a new story for our button.

Now that you learn how to create stories, its your turn to explore this tool and create amazing libraries of your components for your projects
