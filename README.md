## Forkify - Recipe App
Forkify is a recipe application written in vanilla JavaScript that allows users to search and display recipes from the [Forkify API](https://forkify-api.herokuapp.com/v2). Forkify uses common JavaScript build tools such as Babel and Parcel to ensure backwards compatibility with older browsers. 

This project was from Jonas Schmedtmann's 'The Complete JavaScript Course' on Udemy. All JavaScript was written by me, but the SASS styling was provided as is. 

- This project is currently hosted on Netlify and can be explored [here](https://forkify-kurtis.netlify.app/).
![image](/forkify.png)


## Features
- **Recipe Search**: Easily search for your favorite recipes.

- **Search Pagination**: Conveniently navigate through search results.

- **Recipe Bookmarking**: Save your favorite recipes for later.

- **Local Storage**: Saves booked marked recipes to local browser storage for data persistence through refreshes.

- **Create New Recipes**: Users can add their own custom recipes.

- **Dynamic Serving Sizes**: Updates ingredients for any recipe when number of servings is changed.

## Forkify Architecture: Main

![forkify-architecture-recipe-loading](/forkify-architecture-recipe-loading.png)

# Part 1: FlowChart (User search, Search Pagination & Async recipe rendering)
- Add recipe search functionality
- Renders paginated search results and navigation
- Renders recipe asynchronously from API
  
![forkify-flowchart-part-1](/forkify-flowchart-part-1.png)

# Part 2: FlowChart ( Bookmark Recipes, Render Bookmarked Recipe, Update Ingredients)
- Bookmark recipes and store them in browser local storage.
- Render the bookmarked recipe when selected by user.
- Update the ingredient amounts when user changes servings.
  
![forkify-flowchart-part-2](forkify-flowchart-part-2.png)

# Part 3: FlowChart ( Show Add Recipe Form, Upload Recipe, Render User Created Recipe)
- Show new recipe from when user click new recipe.
- Upload new recipe to API.
- Render the newly created user recipe.

![forkify-flowchart-part-3](forkify-flowchart-part-3.png)

## Conclusion
Building this application taught me a lot about using vanilla JavaScript to manipulate the DOM, how use build tools to transpile/polyfill, and deploy a front-end application to the edge. If I was to continue development on this application, I would want to improve the create recipe form to allow more natural language with better validation. Additionally, I would want to add a shopping list feature. Users would then be able to add ingredients directly from a recipe to their shopping list. I will likely not continue developing this application and will move on to learning and building with JavaScript frameworks.  





