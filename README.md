# Interactive Map with Restaurant Markers

## Project Description

This project is an interactive map web application that allows users to search for restaurants in a specific area. Users can enter a location into an autocomplete search bar, and the map will display markers indicating nearby restaurants. Clicking on a marker will show more details about the restaurant, such as the name, place ID, and address.

## User Stories

As a travel enthusiast, I want to search for unique restaurants in areas I plan to visit, so that I can create a dining itinerary for my trips.
As a culinary explorer, I want to discover restaurants serving specific cuisines in different cities, so that I can experience authentic flavors when I travel there.
As a vacation planner, I want to find and bookmark restaurants at my travel destination, so that I can ensure a variety of dining options are available when I arrive.
As a business traveler, I want to find restaurants near my conference venue in a city I am not familiar with, so that I can have quick access to meals in between events.
As an event organizer, I want to search for restaurants that offer private dining areas in other cities, so that I can organize dinner meetings or social gatherings.

## Minimum Viable Product (MVP)

Integration with Google Maps to display the restaurants near the place you decide to go.
Autocomplete search functionality to quickly locate points of interest.
The ability to view details of a selected location on the map.

## Technologies

- HTML
- JavaScript
- Google Maps JavaScript API
- Google Places API

## Setup

To run this project, you'll need to have a Google Maps API key. You can obtain one through the [Google Cloud Platform Console](https://console.cloud.google.com/).

1. Clone this repository to your local machine using `git clone`.
2. Replace `YOUR_KEY` in the `map_searching.html` file with your actual Google Maps API key.
3. Open the `map_searching.html` file in a modern web browser to view and interact with the map.

## Usage

Once you've set up the project with your API key, use the following steps to use the app:

1. Open `map_searching.html` in your web browser.
2. Use the search bar to enter the location you're interested in.
3. The map will center on your chosen location and display nearby restaurants as markers.
4. Click on any marker to see more information about that restaurant.
