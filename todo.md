


Thinks abouot how to introduce the main page eg by using https://material.io/guidelines/motion/material-motion.html you can have each main square coming in a material otion kind a way

Also for the mobile version the Shrine example is pretty good of the effect we are trying to achieve https://material.io/guidelines/motion/material-motion.html#material-motion-what-makes-a-good-transition

Try to create a sticky note effect, think about ways to integratrpictures smoothly in the process. Like maybe try to abstract the concept of the Polaroid. Or add some filters which unveil on hover. 

Change the cards so that instead of scaling you change the zindex.

Add some color filters on the smaller pages in the -900px

Maybe have a button to refresh all the home articles. Only have the first page have the featured elements

At the end of the articles give the option to the user o react like buzzfeed/ facebook. 
Add timeout to the loader at route 38; Or maybe add a transition where all the post it pop in like mushrooms with a bit of a fade in efffect or that cool material thingie


[] fix the scss problem in production


Thing about the best way to introduce the blogpost eg map method v 
Should store the value of fetch in a variable then propagate it. 
Think about introducing a  statemnt to catch if the result of the fetch is null


should I have an other db with sluf matched with ids to find stuff more quickly in the db?

Make all of the Home elements squares to remind of the post its and have colorful borders. aybe put the otpion inn the cms to change the color by adding an element qchi we can include in the style={};

For the data loading use example 2 of : https://jimmylv.gitbooks.io/reactjs-in-meteor-doc-zh/content/docs/meteor-data.html

Next to the blog picture have some sticky notes which are comments from users comme des languettes. or maybe it can be a consteltion of related recipes.

[] Make the loader appear immediately 

See if the  findRelatedPosts function in blogpost.jsx is good and maybe if the limit is too high, it seems like there would be more performent methods of finding tags. Also How to make sure that all these posts fetched are not still in memory somewhere using valuable space.

Reorganize the state of blogpost.jsx have: main-post{slug, content, image}, nextpost{} maybe deal with the fact that we can have multiple posts so create that content dynamicaly


				<Link to={{pathname:this.state.nextPostslug}}>Next Slug</Link>
this will kill the app you have to Change all the states when the slug changes. Now everytime I change from one slug to the other the CPU catches fire

In order to delay the queries without slowing down the page display maybe we should add the queries inside of compoenents which are only loaded when everything is mounted

[] Improve the searching code and make it adapt to : no similar tag found, find multiple other posts. 

[]Problem with the display flow. You should first display the main blog post, then fetch the data for the next 

[] Images have description don' t forget to include that in the alt

[] Limit the ttle lenghts

Later maybe create a version with yeoman to adapt to your headless cms. 
Also create a version which is completely headless. 

Int the IMage conponent you have to add the alts. 

It needs to become SEO friendly!
	[]Use the post tags and display them
	[] Create tag links, you click on them and have access to a page with all posts with same tags
	[] Make good use of title-tag https://moz.com/learn/seo/title-tag

Google recommendations:
	[]Build service workers
	[] Make it mobile friendly!
	[] HTTPS//HTTP2
	[] Fallback if no JS
	[] Add meta viewport


 Its is fucking slow on mobile!!
For the service workers see the implementation of create-react-app
[]Find a way to Improve the display and disappearance of the bigStory Loader when all images are loaded

[] reorganize blogpost to sepearte the logics

[] Still have to cache the next post picturem maybe if the picture isn't loaded also have something to prefill.
[] When a link is clicked on mobile make sure there is some sort of splash animation

[] Reverse the fetch chronological order at home page oso the latest posts appear first. 

[] Create a twitter/instagram bot which posts  the title and hashtags of new post

[] when you unpublish something make sure the people who read wont experience trouble
[] For the mobile version query smaller images.
[] Make sure that the animation runs before anything is loaded especially on mobile.

[DONE!] there is a weird bug, where the picture seems loaded but I can't click it immediately

[] Inspect the bug, after navigating to a page if I relaod it it probably have to deal with it in the CompoenentUnmount of the blogpost.jsx

[] For optimization of delivery watch the video INstant Loading: 3 key user moments