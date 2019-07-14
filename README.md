## Blogposts

Simple react-redux app for fetching blog posts and authors using [JSONPlaceholder](https://jsonplaceholder.typicode.com).

The app fetches list of blogposts first, and then for each blogpost fetches author information. To avoid multiple network requests for overfetching author's information memoization from lodash library is used.

## To run this app

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

