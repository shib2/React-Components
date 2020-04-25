This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

Task 1

In this task you will be adding a new DishdetailComponent to your React application and include the component into the menu component's view so that the details of a specific dish are displayed there:

    Replace the card showing the selected dish in MenuComponent's view with the DishdetailComponent, and make sure to pass the selected dish information as props to the DishdetailComponent.
    Create a new DishDetail class in a file named DishdetailComponent.js in the components folder
    Export the DishDetail class from this file so that it can be imported in MenuComponent.js and used to construct the view of the selected dish.
    Return a <div> from the render() function. This <div> should use the Bootstrap row class to position the content within the <div>. This div will display both the details of the dish in a Card and the list of comments side-by-side for medium to extra large screens, but will stack them for xs and sm screens.
    The card should be enclosed inside a <div> appropriate Bootstrap column classes so that it occupies the entire 12 columns for the xs and sm screen sizes, and 5 columns for md screens and above. Also apply a class of m-1 to this div.
    The comments should be enclosed in a <div> to which you apply appropriate column classes so that it occupies the entire 12 columns for the xs and sm screen sizes, and 5 columns for md screens and above. Also apply a class of m-1 to this div.
    If the dish is null then you should return an empty <div>

Task 2

In this task you will be adding a card component to the DishdetailComponent view to display the details of the dish given above:

    Implement a function named renderDish() that takes the dish as a parameter and returns the JSX code for laying out the details of the dish in a reactstrap Card. You have already seen this as part of the MenuComponent class in the exercise earlier.

    Display the name of the dish as the Card title, and the description as the Card text.

Task 3

In this task you will use the comments that are included in the dish object above to display a list of the comments for the dish. Please use your JavaScript knowledge to recall how you would access an inner property in a JavaScript object that itself points to an array of JavaScript objects (comments). This task involves the following steps:

    Implement a function named renderComments() that takes the comments array as a parameter and lays out each comment as shown in the image below. You should use the Bootstrap list-unstyled class on the list.
    Each comment should be displayed on two lines, the first one showing the comment, and the second line showing the comment author's name and the date.
    The comments should contain a <h4> header with the word "Comments".
    Remember to enclose the header and comments inside a <div> before returning the JSX code. Otherwise React will not do the layout correctly.
    If the comments are null, then you should return an empty <div>.
![tasks](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/du_hMzlMEei9LwoRWz3xkg_5b30647387dc5217ff2ee2c5c86e2fe3_Assignment1.png?expiry=1587945600000&hmac=QvTnBU6MLaQCLdSENCc9C8CQKGz3_ka-mWaOdCht14w)
