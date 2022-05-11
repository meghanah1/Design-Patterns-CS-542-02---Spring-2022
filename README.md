# Design-Patterns-CS-542-02 - Spring-2022

Binghamton University

Professor : Leslie Lander

Assignment 1:

In ViewDriver, add a 4th button to call for the CenterModifier.

Make a class CenterModifier.java by copying and modifying RightModifer.java

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Assignment 2 :

In the Zip file there is a modified composite/iterator version of the textbook's menus. Notice that one of the menus uses an array. The other three use an ArrayList. Apart from the fact that you need to specify the array length, the two menus are interchangeable. 

Assignment: Create a similar application where there are composite objects, leaf objects and at least one sub-level of composite objects stored by another composite (the way a dessert menu is stored by the Diner menu).

I propose that you do one of the following two but if you want to suggest a different application, get my approval as soon as possible.

Version 1. The leaf object is a photo descriptor (we do not need the actual image) but we need the date of the photo and a brief text description that can be search later (could be the place name and the people in the picture if any). The composite object is an album -- this is up to you but one idea is that you can group photos by events or by month and then group your albums by year. 

The important thing is that some album or albums is a sub-album of another album.
Create an iterator to show that you can print all the albums with headings and photos with their descriptions.
Add a search feature so that you can iterate through the photos searching for something like a place name or a person name. This can be a single word search.
Use ArrayList for some composites and array for others
Version 2: Instead of photos use movies (you can get lots of info from https://www.imdb.com). A leaf is a movie. Pick some few details of the movie to store that you could search on later. The composites have to be arranged so they can be in a hierarchy. Maybe genre is one grouping property and year of release could group those genre groups together.

The important thing is that some composite is a sub-composite of another composite.
Create an iterator to show that you can print all the composites with headings and movies with their descriptions.
Add a search feature so that you can iterate through the movies searching for something like a title word or a actor name. This can be a single word search.
Use ArrayList for some composites and array for others.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Assignment 3:

Visitor Pattern : From  Assignment 2 and separate out the actions that have been coded when traversing the composite structure to use Visitors.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Assignment 4 :

PFA the details in attachment.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
