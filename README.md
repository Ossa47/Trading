# VFTE Trading Indicator (Pine Script v5)

## Overview
This repository contains a comprehensive Pine Script (v5) indicator for TradingView. It combines Volume Profile analysis, Supply and Demand zone mapping, Break of Structure (BOS) detection, and trend visualization using EMAs and a ZigZag indicator.

## Key Features
* **Volume Profile (Orderbook):** Plots volume nodes and Point of Control (POC) directly on the chart using customizable rows and widths.
* **Supply & Demand Zones:** Automatically calculates and draws supply and demand boxes based on swing highs/lows, utilizing ATR for zone sizing while preventing overlaps.
* **Break of Structure (BOS):** Detects when the price breaks a valid supply or demand zone and dynamically converts it into a BOS label.
* **Price Action Labels:** Identifies and labels structure points: Higher Highs (HH), Lower Highs (LH), Higher Lows (HL), and Lower Lows (LL).
* **Trend Indicators:** Built-in 50-period and 200-period Exponential Moving Averages (EMA).
* **ZigZag:** Visualizes market swings for clear trend identification.

## How to Install & Use
1. Open [TradingView](https://www.tradingview.com/).
2. Open the **Pine Editor** at the bottom of the chart.
3. Clear any existing code and paste the script.
4. Click **Add to Chart** or **Save**.
5. You can customize the box widths, lengths, and colors via the indicator's Settings menu (gear icon).

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).
© Ossa47
