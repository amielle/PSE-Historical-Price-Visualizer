# PSE Historical Price Visualizer

![alt text](https://github.com/amielle/PSE-Historical-Price-Visualizer/blob/master/img/sample.png "Sample image of site")

[A simple tool](https://pse-prices.herokuapp.com/) deployed on Heroku to display the closing stock price and trading volume data for Blue Chip companies in the Philippines (up to 09/10/19). Built with D3.js, Node.js, HTML, CSS, and plain JS.

Visualization for the stock chart was built on top of [Arnaud Drizard's](https://github.com/arnauddri/d3-stock) work. Modifications include handling of stock data, chart initialization for brush zooming, and aesthetics.

This was made as a toy example to explore the capabilities of D3.js and largely for practice.

Major requirements:
```
sudo apt-get install nodejs
npm install stylus -g
```

To start it locally:
```
http-server src
```
or 
```
npm start
```
