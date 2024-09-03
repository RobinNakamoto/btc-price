# BTC Clock

BTC Clock is a minimalist web app that displays the live price of BTCFDUSD (a Bitcoin trading pair) fetched from the Binance API. The app is designed to be simple, fast, and responsive, making it easy to monitor Bitcoin prices in real-time.

## Features

- **Real-time Price Updates:** Fetches the latest BTCFDUSD price every second from the Binance API.
- **Responsive Design:** The app is optimized for both desktop and mobile viewing.
- **Progressive Web App (PWA):** Can be installed on your device and works offline thanks to the service worker.

## Installation

You can access the BTC Clock directly from [GitHub Pages](https://robinnakamoto.github.io/btc-price) or follow the instructions below to run it locally.

### Running Locally

1. Clone the repository:

    ```bash
    git clone https://github.com/RobinNakamoto/btc-clock.git
    cd btc-clock
    ```

2. Open `index.html` in your web browser.

## Project Structure

- **index.html:** The main HTML file that structures the web page.
- **manifest.json:** Configuration for the web app, including icons and theme colors.
- **renderer.js:** JavaScript file responsible for fetching the BTCFDUSD price and updating the DOM.
- **service-worker.js:** Handles offline capabilities and caching of app assets.
- **icons/:** Directory containing various icons for different devices and platforms.

## Usage

Simply open the web app, and it will display the current price of BTCFDUSD with updates every 200 milliseconds. The price color will change to green when the price goes up and red when it goes down, making it easy to see the trend at a glance.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
