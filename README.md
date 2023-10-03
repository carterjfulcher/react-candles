# React Candles

> **Note:** this repo originates from [react-stockcharts](https://github.com/rrag/react-stockcharts). It was converted to typescript by `react-financial` under the name, `react-candles`, and in this latest fork, `react-candles` functional components and realtime support was added.

## Features

-   integrates multiple chart types
-   technical indicators and overlays
-   drawing objects

### Chart types

-   Scatter
-   Area
-   Line
-   Candlestick
-   OHLC
-   HeikenAshi
-   Renko
-   Kagi
-   Point & Figure

### Indicators

-   EMA, SMA, WMA, TMA
-   Bollinger band
-   SAR
-   MACD
-   RSI
-   ATR
-   Stochastic (fast, slow, full)
-   ForceIndex
-   ElderRay
-   Elder Impulse

### Interactive Indicators

-   Trendline
-   Fibonacci Retracements
-   Gann Fan
-   Channel
-   Linear regression channel

---

## Installation

```sh
npm install react-candles
```

## Documentation

[Stories](https://react-financial.github.io/react-candles/)

## Contributing

Refer to [CONTRIBUTING.md](./CONTRIBUTING.md)

This project is a mono-repo that uses [Lerna](https://lerna.js.org/) to manage dependencies between packages.

To get started run:

```bash
git clone https://github.com/react-financial/react-candles.git
cd react-candles
npm ci
npm run build
```

To start up a development server run:

```bash
npm start
```
