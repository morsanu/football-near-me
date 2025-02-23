# Football Fixtures Finder

A web application that helps users find football matches based on location. Users can search for matches by country or city, and find fixtures within a 100km radius of their selected location.

## Features

- **Unified Search**: Single search box for both countries and cities
- **Location-based Search**: Find matches within 100km radius of selected location
- **Distance Display**: Shows how far each match is from the selected location
- **Nearby Matches**: Button to find matches near user's current location
- **Responsive Design**: Works on both desktop and mobile devices

## Data Structure

The application uses two main data files:

### 1. fixtures.json
Contains match information including:
- Match details (teams, time, competition)
- Venue information
- Coordinates
- Team logos
- Competition details

### 2. counties+cities.json
Contains geographical data:
- Countries with their emoji flags
- Cities with coordinates
- Used for location-based searching

## Usage

1. **Search for Location**:
   - Type a country or city name in the search box
   - Results will show with country flags
   - Select from the dropdown list

2. **View Matches**:
   - For country selection: shows all matches in that country
   - For city selection: shows matches within 100km radius
   - Distances are shown in kilometers

3. **Find Nearby Matches**:
   - Click the "Find Nearby Matches" button
   - Allow location access when prompted
   - View matches within 100km of your current location

## Technical Details

- Pure JavaScript (no frameworks)
- Geolocation API for nearby matches
- Distance calculation using Haversine formula
- Responsive CSS design

## Setup

1. Clone the repository
2. Ensure you have the required data files:
   - `fixtures.json`
   - `counties+cities.json`
3. Open `index.html` in a web browser

## Browser Support

Works in all modern browsers that support:
- Geolocation API
- ES6+ JavaScript
- Modern CSS features

## Contributing

Feel free to submit issues and enhancement requests!

## License

[Your chosen license] 