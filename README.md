# UFO Sightings

***Overview***

On this assignment I got to build a dynamic webpage that accepts user inputs and visually adjust to reflect that interaction. My task was to build a dynamic table to holds and display UFO sightings in the United States. I added filters to the table which let users refine their search on more than one level. The table was inserted into, and visually displayed by an HTML page and I also took advantage of CSS and Bootstrap to stylize the page.

***Results***

The webpage allows multiple filters at the same time for the user, including: Date, City, State, Country, and Shape. The user can enter one or any number of these filters to return the filtered table displayed on the page.

Searching with different filters is quite simple, all you need to do is the following:

- The user needs to enter a value on any of the "Filter Search" fields, such as: a date, a city, a state, a country and/or a shape.

<img width="491" alt="Screen Shot 2020-12-07 at 3 25 37 PM" src="https://user-images.githubusercontent.com/70611325/101417511-a9d28100-38a0-11eb-9600-6005e9fd03d9.png">

- After the user adds the values in the search fields of the filters they want to use, on the right of the webpage, a new filtered table will be populated based on the values that the user added. For example, let's imagine I want to search for UFO Sightings that occured on 1/12/20 but only in CA:

<img width="1437" alt="Screen Shot 2020-12-07 at 3 39 27 PM" src="https://user-images.githubusercontent.com/70611325/101418498-e0a99680-38a2-11eb-9ce8-f150184095fb.png">
 
See in the snapshot above that the user doesn't need to fill every search field, because if a value was not entered then the element id will be cleared from the filters variable and it will make de search with only the values that were entered.

- To clear the filters, reset the webpage and reload the default unfiltered table, the user needs to click on the link that's called "UFO Sightings" at the top right of the entire page.

<img width="1438" alt="Screen Shot 2020-12-07 at 3 13 07 PM" src="https://user-images.githubusercontent.com/70611325/101419436-db4d4b80-38a4-11eb-845e-4d36e9b80cd1.png">

***Summary***

The dynamic webpage page looks clean and allows the user to filter through the dataset using the filter search fields created. 

I must say that a drawback about this dynamic webpage is not having information about UFO sighting of countries all around the world.

My two recommendations for improving the webpage are:

1. Add more key information, as for example, how many people witnessed the sightings, to make our webpage more trustworthy.

2. Constantly update the database by adding new information, this way the table will reflect the most recent UFO Sightings.
