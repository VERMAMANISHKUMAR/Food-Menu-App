# Features and Functionality Breakdown
## HTML File (index.html)
Page Title and Metadata:

Title set as "Food Ordering App".
Includes responsive viewport settings for mobile compatibility.
Imports Google Fonts (Montserrat) for consistent typography.
Includes Font Awesome icons for search and ratings.
Header and Navbar:

Contains a logo image (lastmeal.png).
Displays a greeting message with user personalization (Morning Suman).
Search bar integrated with a placeholder and search icon.
Fixed header with a shadow effect for a clean look.
Main Section:

A header titled "Top restaurants in your area".
Dropdowns for sorting by Rating or ETA (Estimated Time of Arrival).
Dropdown for filtering restaurants based on food type (e.g., American, Indian).
Section (#restaurant-list) for dynamically displaying restaurant cards.
JavaScript and External Resources:

Links to style.css for styling.
Loads Font Awesome JavaScript library.
Includes app.js for functionality.
JavaScript File (app.js)
Restaurant Data:

An array of 15 restaurant objects with details like id, name, location, rating, ETA, tags, and image.
**Dynamic Restaurant Display:**

Function displayRestaurants dynamically renders restaurant details into the #restaurant-list section.
Displays the following for each restaurant:
Image, name, location, rating (with stars), ETA, and tags.
Search Functionality:

Implements a search bar that filters restaurants based on user input.
Converts search queries to lowercase for case-insensitive matching.
Filter and Sort Options:

Filters restaurants based on the selected food type (e.g., American, Indian).
Sorts restaurants by:
Rating: Highest to lowest.
ETA: Shortest to longest delivery time.
Debouncing for Search:

Uses a debounce function to delay search queries, improving performance by reducing redundant calls.
Event Listeners:

Updates the restaurant list dynamically as users type in the search bar or change sorting/filter options.
Initial Rendering:

On page load, displays the entire list of restaurants.
# CSS File (style.css)
## Global Styling:

Applies Montserrat font to all elements.
Resets margin, padding, and box-sizing.

## Navbar Styling:

Fixed at the top with a height of 80px and a border-bottom for separation.
Includes shadow for a clean elevation effect.
Logo aligned on the left; user greeting and search bar aligned to the right.
Restaurant List Styling:

Individual restaurant cards (.restaurant-details) include:
Image styling for proper aspect ratios.
Rating display with stars using Font Awesome icons.
Tags displayed as a comma-separated list.
Responsiveness:
Layout ensures compatibility across various screen sizes.
# Summary of Features
**Dynamic Content: Restaurants are displayed and updated based on user inputs.**
**Sorting and Filtering: Provides user-friendly ways to find restaurants quickly.**
**Debounced Search: Optimized search for seamless user experience.**
**Modern UI: Clean and responsive design with consistent styling and functionality.**






