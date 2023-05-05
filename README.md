# Atlante3d

## The idea

This is my first project as a freelance developer! Atlante is creating an EV charging network across Europe. They want to create a 3d website to showcase the charging experience you'll get in their stations.

The website will be divided in 2 parts. At first we'll show the charging station with as many details as we can. Once the user has checked out the station, he will be able to discover the whole place with all the elements around the charging spots.

[Live](https://www.atlante-3dexperience.com/)

## Features

### The charging spot

This is the part of the website. We want to add 6 points of interest to showcase the charging spot. Every time the user clicks on a point, the camera will zoom on the 3d element and some text details will appear to add some context and applications.

It was pretty easy to animate the camera on click of a POI (point of interest). We added a button to reset the camera position so the user can come back to the default position. He doesn't need to come back every time too. The POI will still be displayed so he can switch in between them.

Once the whole experience was created, we created the same experience with free camera movement to add the perfect camera positions for the POIs.

### The whole station

This was the hardest part of the website.
We want the user to explore the station and discover the place. To do that we will dispatch the main elements around the station and make the user slide around. We'll add context when the camera is in front of an item. The user will be able to vote so Atlante know the interest of each point.
