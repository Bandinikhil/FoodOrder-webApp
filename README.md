# JustEat FoodOrdering WebApp

JustEat is a web application designed to help you explore restaurants and enjoy your dining experience. This README will provide an overview of the project's key features, technologies used, and development practices.

## Deployed link :-   🔗 https://justeatwebapp.netlify.app/

![Screenshot (110)](https://github.com/Bandinikhil/FoodOrder-webApp/assets/105233916/10be34e0-206e-4370-abd5-9
![Screenshot (111)](https://github.com/Bandinikhil/FoodOrder-webApp/assets/105233916/db97c08c-04fb-4c41-b5d9-c1eae406d301)
b0c90ba7b02)
![Screenshot (112)](https://github.com/Bandinikhil/FoodOrder-webApp/assets/105233916/86f9eee4-4781-4858-88e3-639fe9585482)

## Development Build Features

- **Local Server**: We utilize a local server to test and develop our application.

- **HMR (Hot Module Replacement)**: HMR allows us to see the changes we make to the code in real-time without the need to reload the entire application.

- **File Watching Algorithm**: Our file watching algorithm is written in C++ for efficient monitoring of file changes.

- **Caching**: Caching is implemented to speed up build processes, resulting in faster development builds.

- **Image Optimization**: We optimize images to ensure fast loading times and a smooth user experience.

- **Minification**: Our code is minified for production to reduce file sizes and improve loading times.

- **Bundling**: We bundle our code to combine multiple files into a single file for efficient loading.

- **Compression**: Our application's assets are compressed to minimize bandwidth usage.

- **Consistent Hashing**: We employ consistent hashing for load balancing and efficient data distribution.

- **Code Splitting**: Code splitting is used to optimize page loading and reduce initial loading times.

- **Differential Bundling**: We support older browsers by providing bundles that cater to their specific requirements.

- **Diagnostic Error Handling**: We have robust error handling in place for efficient debugging and issue resolution.

- **HTTPS**: Our application supports secure communication via HTTPS for user data protection.

- **Tree Shaking**: We eliminate unused code using tree shaking to optimize the application's performance.

- **Different Dev and Prod Bundles**: We have distinct development and production bundles to enhance the development experience.

## Components

- **Header**: The header section of the application.
  - **Logo**: The application's logo.
  - **Nav Items**: Navigation items for easy access.

- **Body**: The main content of the application.
  - **Search**: The search feature for finding restaurants.
  - **Restaurant Container**: A container for displaying restaurant information.
  - **Restaurant Card**: Cards containing restaurant details.
    - **Image**: An image representing the restaurant.
    - **Name of Restaurant, Star Rating, Cuisine, Delivery Time**: Key information about the restaurant.

- **Footer**: The footer section of the application.
  - **Copyright**: Copyright information.
  - **Links**: Important links.
  - **Address**: Contact address.
  - **Contact**: Contact details.

## Export/Import Types

- **Default Export/Import**: 
  - Export: `export default Component;` 
  - Import: `import Component from "path";`

- **Named Export/Import**: 
  - Export: `export const Component;` 
  - Import: `import {Component} from "path";`

## React Hooks

- We use React Hooks, which are normal JavaScript utility functions.
  - `useState()`: For managing state variables in our application.
  - `useEffect()`: For handling side effects.

## Routing

Our application employs two types of routing in web development:

- **Client Side Routing**: For a seamless user experience within the browser.
- **Server Side Routing**: For navigating to different pages on the server.

## Redux Toolkit

We use Redux Toolkit for state management. To set it up, follow these steps:

1. Install `@reduxjs/toolkit` and `react-redux`.
2. Build our store.
3. Connect our store to our app.
4. Use slices (e.g., `cartSlice`) for managing state.
5. Dispatch actions.
6. Utilize selectors to access specific state data.

## Types of Testing

As developers, we perform three types of testing:

- **Unit Testing**: Testing individual components or functions.
- **Integration Testing**: Testing the interaction between different parts of the application.
- **End-to-End Testing (E2E Testing)**: Comprehensive testing of the entire application.

## Setting up Testing in Our App

To set up testing in our application, follow these steps:

1. Install React Testing Library.
2. Install Jest.
3. Install Babel dependencies.
4. Configure Babel.
5. Configure Parcel Config file to disable default Babel transpilation.
6. Set up Jest using `npx jest --init`.
7. Install the jsdom library.
8. Install `@babel/preset-react` to make JSX work in test cases.
9. Include `@babel/preset-react` inside your Babel config.
10. Install `@testing-library/jest-dom`.

This README provides an overview of the Namaste Food project, its key features, technologies used, and development practices. It serves as a comprehensive guide to help you understand and contribute to the project.
