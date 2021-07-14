# Movie app
<br />
* Build a movie app that include the following pages:<br />
<br />
2. <b>Form page</b>  <br />
    A form of Movie with create/edit option<br />
    The form should have a cancel button when clicked the user back to where he came from.<br />
    The form should have a create button that save a new/edited movie to the movies list.<br />
    <br />
2. <b>Movie list</b><br />
    A list of all movies, with create new movie button that open the create movie form <br />
    >  each movie in the list is a box witch includes a thumbnail image, a title and short description text.<br />
    Clicking on the movie box will open the details page with the long description text.<br />
    Also add an 5 rating stars (!!!we didn't supplied design for the rating starts but we expect that you'll add it.<br />
    The stars are gray to emphesize empty.<br />
    When you press on the star it become full yellow(it need to be toggle).<br />
    A movie is an object that has the following properties **at least**:<br />
    {name, year, derector, image, categoryIds[],id(auto generated when you create)}<br />
<br />
3. <b>Details page</b><br />
    A details movie page with edit button that open the edit form.<br />
    Include in the page a big image of the movie.<br />
    Beneath the image there are 5 stars to add retaing.<br />
    Beneath the image there's a title and a long description text.<br />
    Beneath it also includes a category list (action, drama ...).<br />
<br />
``` Movies that have been created/edited, and the rating stars that you gave it should be displayed after refreshing the page ```<br />
<br />
<br />
### general info
Use the attached images as a guidlines. This is not a pixel perfect and we don't expect it to be amazing but it should be nice,aligned and responsive with flex.<br />
Use react-router to browse between pages.<br />
You'r routes should be:<br />
<b>/</b>  - for the list.<br />
<b>/details/movieId</b>  - for the details (movieId is the id of the movie).<br />
<b>/create</b> - for create a new movie.<br />
<b>/edit/movieId</b> - for edit a movie details (movieId is the id of the movie).<br />
<br />
Use a free movies api to fetch a real data. (a list for example - https://public-apis.io/free-movies-apis-collection)<br />
be sure it provides all your data needs.<br />
This api should include also a trailer for the movie if you are going to deliver the movie trailer bonus mission.<br />
Use any lib that you find fits for completing the mission.<br />
<br />
If you know typescript you should build it with typescript.<br />
<br />
Use react functional components and hooks only (no class component though knowlage of class lifecycle are required).<br />
Be organazied, and keep your code neat and readable. bonus: try to be efficent.<br />
<br />
Use the pictures as a guidelines.<br />
All the pages including the form should be responsive, and be should be displayed nicely on mobile(not native but web view) and desktop with flex approach.<br />
The app should be based on flex/grid design.<br />
<br />
Bonus:<br />
(The bonus is not required though it can improve your odds among other candidates).<br />
<br />
1. Build a trailer modal:<br />
    - The trailer should be opened as modal with dark layer.<br />
    - When you click on the item in the movie list it opens the modal and start playing the movie trailer.<br />
    - For this mission use the movies api of your choice that includes also trailers.<br />
<br />
2. Add my favorites movies page: <br />
    The route for this will be <b>/my-movies</b><br />
    For this you should add + button to each of item.(make it toggle button, green is the indicator for saved and gray for removed/not saved).<br />
    To be clear when you klick the + this movie will be added to the favorites<br />
    Add a header with the <b>My-movies|All movies</b> links to browse between the two.<br />
<br />
<br />;
<h3>How to deliver</h3>
Create your github account a public github repository named MoviesOnTheTrain.<br />
Upload your files to the repo.<br />
Add a demo static page with github pages. <br />
The README.md file should have only a title and a link with the demo(e.g. (myuser.github/repo.git)[demo])<br />
<br />
to create the project use the command:<br />
npx create-react-app movies-on-the-train --template typescript<br />
<br />
When it's ready contact your contact through the mail or phone.
