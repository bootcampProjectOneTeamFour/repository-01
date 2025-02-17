# Food Finder

Many people often take where they live for granted, even in urban locales surrounded by stores and restaurants and can end up missing out on some nearby neighbourhood gems.  Or perhaps they just don't want to get in a car, or Uber, to dine out at one of the better known restaurants. The purpose of our product is to provide the user with options for great restaurants within a convenient walking distance from their home; just around the corner.

[An Introduction to Food Finder](https://docs.google.com/presentation/d/18xuyFBQ4i-O3lLa5vpeEBHfx4rvo2I6NJQ5TWFbmqzM/)

## Built With

- HTML
- Tailwind CSS
- Javascript
- Yelp Fusion API
- Google Geocoding API
- Google Directions API

## Design and Functionality

The main design uses a combination of HTML, CSS and Javascript.

1/ The user inputs their postal code into the search field and then clicks on the "Food" button.

![screenshot of homepage with postal code input field](assets/images/food-finder-index.html-screen-shot.png)

2/ The button click calls the function that pulls information from the Yelp Fusion API display the top 10 rated restaurants in the user's area.

![screenshot of homepage displaying search results](assets/images/food-finder-restaurant-display-screen-shot.png)

3/ When the user clicks on the restaurant button, that click calls the function that pulls information from a combination of the Open Route API, and Google Maps to display walking directions to that restaurant.

![screenshot of directions page for site]("./../assets/images/restaurant-index-page-reformatted.png)

4/ At the same time, the button click saves the user's search history into local storage so that when the user returns to the restaurant directory, the user's search history will be displayed.

![screenshot of homepage showing previous searches retrieved from local storage](assets/images/food-finder-page-back-localstorage-search-display-screenshot.png)

## Deployment

This site has been published via [Github Pages](https://bootcampProjectOneTeamFour.github.io/food-finder/)
The repository has been stored on [Github](https://github.com/bootcampProjectOneTeamFour/food-finder)

## Installation

The first time you run Food Finder, you will get a console 403 error.

- Click on the "https://cors-anywhere.herokuapp.com/" link and allow temporary access.
- Return back to Food Finder and refresh the page.
- You should have no longer have any issues finding great food!

## License

An MIT [License](LICENSE) has been included with this project.

## Credits and external Resources

- Yelp Fusion - <https://fusion.yelp.com/>
- Google Geocoding - <https://developers.google.com/maps/documentation/geocoding>
- Google Directions - <https://developers.google.com/maps/documentation/directions>

## Future Developments

- When the user searches by postal code, they are shown a map of the top 10 best rated restaurants in that area
- When a user clicks on the pin for that restaurant, they are shown a badge. If the user clicks on that badge, they are directed towards the restaurant’s website.

## Project Contributors

- Ian Ackerman (<https://github.com/ianaack>)
- Laurel David (<https://github.com/lnd4812>)
- Tommy Otis (<https://github.com/xdatalinq>)
- Matthew Smith (<https://github.com/mdubb23>)
- Feven Tsegai (<https://github.com/feventsegai>)
