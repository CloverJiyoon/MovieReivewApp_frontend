# Movie Review App

Deployed Link : https://movietime-frontend-clover.herokuapp.com/

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Screenshots

### _Step 1: Implementing Frontend_
---
- Displayed as below at localhost:3000 

 ![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/localhost3000.png)

- Each movie's 'Reviews' page is displayed as below

![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/TheGreatTrain.png)


- The movies without poster image is displayed as below

![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/placeholder.png)

---


### _Step 2: Set up Authentication and Reviews_
---
- Google Cloud Platform API was used to authenticate users.

 ![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/NewReview.png)
 *Screenshot of a movie review page with a newly written review*

![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/EditedReview.png)
*Screenshot of the same page with the review edited*

---


### _Step 3: Set up Favorite features for logged in users_
---
- Any logged in user can save their favorite move by clicking the movie posters. Star on each poster will change from white to yellow color when they want to mark as their favorite movie.

 ![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/FavoriteStars.png)
 *Screenshot of a movie landing page for logged in user*

![Image Link](https://github.com/CloverJiyoon/MovieApp_Image/blob/main/FavoriteMongoDB.png)
*Screenshot of the favorite list database table from MongoDB Compass*

---



## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

