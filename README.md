# Passing Thoughts - React App

This project is a simple React application that allows users to add and remove "passing thoughts". This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), a popular tool for creating React projects quickly. 

## Function Components and Hooks:

The Passing Thoughts app utilizes React's Function Components and Hooks to manage state and create dynamic user interfaces. In particular, the app uses the following Hooks:

### The State Hook

New thoughts are stored in State using the useState Hook. This allows the app to keep track of the user's input and update the interface in real time. The user can also manually remove thoughts from the list.

### The Effect Hook

Or each new thought is automatically removed after 15 seconds using the useEffect Hook. This ensures that the app stays responsive and does not become cluttered with old thoughts.

### Getting Started

To run this app on your local machine, you'll need to download the necessary dependencies using npm install. Once the dependencies are installed, you can start the app by running npm start in the command line.

I hope you enjoy using the Passing Thoughts app!

Created by Jay Lee with the help of [Codecademy](https://www.codecademy.com/learn) courses.
