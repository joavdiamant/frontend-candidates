# Movie app

* Build a movie app that include the following pages:

1.  **Form page** 
    A form of Movie with create/edit option
    The form should have a cancel button when clicked the user back to where he came from.
    The form should have a create button that save a new/edited movie to the movies list.
    
2. **Movie list**
    A list of all movies, with create new movie button that open the create movie form 
    >  each movie in the list is a box witch includes a thumbnail image, a title and short description text.
    Clicking on the movie box will open the details page with the long description text.
    Also add an 5 rating stars (!!!we didn't supplied design for the rating starts but we expect that you'll add it.
    The stars are gray to emphesize empty.
    When you press on the star it become full yellow(it need to be toggle).
    A movie is an object that has the following properties **at least**:
    {name, year, derector, image, categoryIds[],id(auto generated when you create)}

3. **Details page**
    A details movie page with edit button that open the edit form.
    Include in the page a big image of the movie.
    Beneath the image there are 5 stars to add retaing.
    Beneath the image there's a title and a long description text.
    Beneath it also includes a category list (action, drama ...).

``` Movies that have been created/edited, and the rating stars that you gave it should be displayed after refrashing the page ```



### general info
Use the attached images as a guidlines. This is not a pixel perfect and we don't expect it to be amazing but it should be nice,aligned and responsive with flex.
Use react-router to browse between pages.
You'r routes should be:
**/**  - for the list
**/details/movieId**  - for the details (movieId is the id of the movie)
**/create** - for create a new movie.
**/edit/movieId** - for edit a movie details (movieId is the id of the movie)

Use a free movies api to fetch a real data. (a list for example - https://public-apis.io/free-movies-apis-collection)
be sure it provides all your data needs.
This api should include also a trailer for the movie if you are going to deliver the movie trailer bonus mission.
Use any lib that you find fits for completing the mission.

If you know typescript you should build it with typescript.

Use react functional components and hooks only (no class component though knowlage of class lifecycle are required).
Be organazied, and keep your code neat and readable. bonus: try to be efficent.

Use the pictures as a guidelines
All the pages including the form should be responsive, and be should be displayed nicely on mobile(not native but web view) and desktop with flex approach.
The app should be based on flex/grid design.

Bonus:
(The bonus is not required though it can improve your odds among other candidates).

1. Build a trailer modal:
    - The trailer should be opened as modal with dark layer.
    - When you click on the item in the movie list it opens the modal and start playing the movie trailer.
    - For this mission use the movies api of your choice that includes also trailers.

2. Add my favorites movies page: 
    - The route for this will be **/my-movies**
    -  For this you should add + button to each of item.(make it toggle button, green is the indicator for saved and gray for removed/not saved).
    To be clear when you klick the + this movie will be added to the favorites
    
     - add a header menu with the favorites, All movies links to browse between the two. it should use the react router lib.
     

## How to deliver
Create a public github repository named MoviesOnTheTrain.
Upload your files to the repo.
Add a demo static page with github pages. 
The README.md file should have only a title and a link with the demo(e.g. (myuser.github/repo.git)[demo])

to create the project use the command:
npx create-react-app movies-on-the-train --template typescript

When it's ready contact your recruiter through the mail or phone.
