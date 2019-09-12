# PSE Historical Price Visualizer

A simple tool to display the closing stock price and trading volume data for Blue Chip companies in the Philippines (up to 09/10/19). Built with D3.js, Node.js, HTML, CSS, and plain JS.

Visualization for the stock chart was built on top of [Arnaud Drizard's](https://github.com/arnauddri/d3-stock) work. Modifications include of handling of stock data, chart initialization for brush zooming, and aesthetics.

This was made as a toy example to explore the capabilities of D3.js and largely for practice.

Requirements:
```
sudo apt-get install nodejs
npm install stylus -g
```

To start it locally:
```
http-server src
```

If you have trouble with http-server, make sure you've [set the path](https://stackoverflow.com/questions/46851400/http-server-command-not-found) for npm :))
