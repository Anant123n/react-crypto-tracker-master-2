# Crypto Hunter

Crypto Hunter is a React-based cryptocurrency tracker that displays real-time prices, market data, and historical charts for popular cryptocurrencies. The application uses the CoinGecko API to fetch cryptocurrency data and Material-UI for a modern, responsive user interface.

![Banner](public/banner2.jpg)

## Features

- **Real-time Cryptocurrency Data**: Track prices, market cap, and price changes for top cryptocurrencies
- **Trending Coins Carousel**: View trending cryptocurrencies in a responsive carousel
- **Search Functionality**: Search and filter coins by name or symbol
- **Pagination**: Browse through the list of cryptocurrencies with easy navigation
- **Detailed Coin Information**: Access comprehensive information about each cryptocurrency
- **Interactive Price Charts**: View historical price data with customizable time periods (24 hours, 30 days, 3 months, 1 year)
- **Currency Conversion**: Toggle between INR (₹) and USD ($) currencies
- **Responsive Design**: Optimized for both desktop and mobile devices

## Technologies Used

- **React.js**: Frontend library for building the user interface
- **Material-UI**: React component library for styling
- **Chart.js & React-Chartjs-2**: For creating interactive price charts
- **Axios**: For making API requests
- **React Router**: For navigation between pages
- **React Alice Carousel**: For the trending coins slider
- **CoinGecko API**: For cryptocurrency data

## Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm or yarn

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/yourusername/crypto-hunter.git
   cd crypto-hunter
   ```

2. Install dependencies
   ```sh
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```sh
   npm start
   # or
   yarn start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Usage

- **Home Page**: Displays a banner, trending coins carousel, and a table of cryptocurrencies
- **Coin Page**: Shows detailed information about a specific cryptocurrency, including price charts
- **Currency Toggle**: Use the dropdown in the header to switch between INR and USD
- **Search**: Use the search bar to find specific cryptocurrencies
- **Time Period Selection**: On the coin page, select different time periods to view historical price data

## Project Structure

```
├── public/                 # Public assets
├── src/                    # Source files
│   ├── components/         # React components
│   │   ├── Banner/         # Banner components
│   │   ├── CoinInfo.js     # Coin chart component
│   │   ├── CoinsTable.js   # Cryptocurrency table
│   │   ├── Header.js       # Application header
│   │   └── SelectButton.js # Time period selector
│   ├── config/             # Configuration files
│   │   ├── api.js          # API endpoints
│   │   └── data.js         # Static data
│   ├── Pages/              # Page components
│   │   ├── CoinPage.js     # Detailed coin view
│   │   └── HomePage.js     # Home page
│   ├── App.js              # Main application component
│   ├── CryptoContext.js    # Context for currency state
│   └── index.js            # Application entry point
└── package.json            # Project dependencies
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [CoinGecko API](https://www.coingecko.com/en/api) for providing cryptocurrency data
- [Material-UI](https://material-ui.com/) for the UI components
- [Chart.js](https://www.chartjs.org/) for the interactive charts