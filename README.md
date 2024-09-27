# Image Search App

This is a simple image search application that allows users to search and view images using the Unsplash API. Users can search for images by keyword and load more results with a "Show More" button.

## Features

- **Image Search**: Search for images using keywords.
- **API Integration**: Fetches images from the Unsplash API.
- **Responsive Design**: Works on both desktop and mobile devices.
- **Lazy Loading**: Load more images as needed with the "Show More" button.
- **Image Links**: Each image is clickable, linking to the full version on Unsplash.

## Technologies Used

- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript (Vanilla JS)
- **External API**: Unsplash API

## File Structure

- `index.html`: Contains the structure and basic layout of the app, including the search bar and image display area.
- `style.css`: Contains the styling of the app, providing a responsive and clean design.
- `index.js`: Contains the logic for interacting with the Unsplash API and displaying images on the page.

## How to Use

1. **Search for Images**: Enter a search term in the search bar and click the search button.
2. **View Images**: The results will display images related to your search.
3. **Load More Images**: Click the "Show More" button to load additional images.

## Setup Instructions

1. Clone the repository or download the project files.
2. Open the `index.html` file in your browser.
3. Enter a search query in the input field and view the image results.

## API Integration

This app uses the [Unsplash API](https://unsplash.com/developers) for fetching images. To run this app with your own API key:

1. Sign up on Unsplash and create a new app to get an API key.
2. Replace the API key in `index.js` at the following line:
   ```javascript
   const accessKey = "your-unsplash-api-key-here";
