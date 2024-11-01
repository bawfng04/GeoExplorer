https://geoexplorer-ed0d5.web.app/

Known issue: News won't work in the web app due to CORS. Still running file locally.

[Lost all commits because of a Git force...]

# GeoExplorer

GeoExplorer is a web application that allows users to explore various countries and cities around the world. Users can select a country and a city to view information such as the country's flag, capital, currency, ISO code, and dial code. Additionally, users can view the location of the selected city in Google Maps, check the current weather in the city, and view news related to the selected city.

## Features

- **Country and City Selection**: Users can select a country and a city from dropdown menus.
- **Country Information**: Displays information about the selected country, including the flag, capital, currency, ISO code, and dial code.
- **Google Maps Integration**: Allows users to view the selected city on Google Maps.
- **Weather Information**: Displays the current weather in the selected city using data from the OpenWeatherMap API.
- **City News**: Shows news articles related to the selected city using data from the NewsAPI.


## Screenshots

<img src="https://github.com/user-attachments/assets/9d74191a-f7aa-4203-b404-45d72cc1f747" width="500px">
<img src="https://github.com/user-attachments/assets/c7666230-0faa-4762-8e26-0b75a0ea9321" width="500px">
<img src="https://github.com/user-attachments/assets/f0c095da-1eff-4f8f-bace-4745204c8660" width="500px">
<img src="https://github.com/user-attachments/assets/46bb7270-3a7c-4a3b-953d-3390fbd3a9e9" width="500px">
<img src="https://github.com/user-attachments/assets/8f5bd3f1-10df-4853-84c6-6677025fdd50" width="500px">

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/geoexplorer.git
   cd geoexplorer
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Project Structure

```
.firebase/
build/
public/
src/
  core/
    Country.css
    CountryInfo.js
    Main.css
    Main.js
    MapsAndWeather.css
    MapsAndWeather.js
    TargetSelector.js
  template/
    Authentication.css
    Footer.js
    Header.js
    Login.js
    Register.js
  App.css
  App.js
  index.js
  reportWebVitals.js
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`

Launches the test runner in interactive watch mode.

### `npm run build`

Builds the app for production to the 

build

 folder. It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run eject`

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
