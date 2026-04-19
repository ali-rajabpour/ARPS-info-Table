<p align="center">
  <img src="https://github.com/user-attachments/assets/4194daa0-ecc7-42b3-a62d-7b96837b4cb9" 
       alt="FileFlow"
       width="60%" />
</p>


# ARPS info Table
**Originally created: April 09, 2023**
*(Note: This script was created in 2023 but is being shared on GitHub on 2025-04-25)*

---

# 📊 ARPS Info Table

**ARPS Info Table** is a powerful TradingView indicator that combines multiple technical analysis tools and displays summarized insights in a clear, organized table format on the chart itself. Designed for traders looking for multi-timeframe confirmations, stop-loss management, and trend identification, this indicator provides all the information at your fingertips.

---

## Features

1. **Multi-Timeframe Moving Averages**:  
   Computes the 200-period Simple Moving Average (SMA) and Exponential Moving Average (EMA) in multiple timeframes:
   - 30 minutes
   - 60 minutes
   - 4 hours
   - 6 hours
   - 12 hours
   - 1 day
   - 1 week

2. **Alligator Indicator**:  
   Implements advanced Alligator trend lines (Jaw, Teeth, and Lips with configurable offsets) along with state analysis for identifying bearish, bullish, or consolidating trends.

3. **Fractals**:  
   Includes Williams Fractal detection for identifying potential reversals and breakout opportunities. Fractal-based reversal signals are plotted as arrows directly on the chart.  

4. **Stop-Loss Management**:  
   Dynamically calculates potential long and short stop-loss levels based on the ATR (Average True Range), enabling effective risk management.

5. **Squeeze Momentum Indicator**:  
   Detects the relationship between Bollinger Bands and Keltner Channels to identify low-volatility periods and potential breakout opportunities. Visualizes long/short squeeze momentum directly within the table.

6. **Real-Time Information Table**:  
   Displays all calculated indicators in a convenient table format located on the chart. This table includes:
   - Moving Averages (SMA and EMA) across all timeframes.
   - Alligator trend direction 🐮 (Bull), 🐻 (Bear), and 💤 (Neutral).  
   - 200-period crossovers visualized with up/down arrows.
   - Squeeze momentum indicator signals for better timing on trade entries.

7. **Customizable Design**:  
   - Enables or disables specific features such as the Alligator state or Fractal breakout strategy.
   - Includes tooltips and emojis for quick interpretation of signals in the table.

8. **Contact Information**:  
   A footer table includes credit to the author for version tracking or inquiries.

---

## How It Works

### Table Overview
The table provides:
- **Stop-Loss Levels**: Displays calculated stop-loss prices for both Long and Short positions.  
- **Alligator Indicator Trend**: Displays the current Alligator state:
  - 🐮 for bullish.
  - 🐻 for bearish.
  - 💤 for neutral/consolidation.
- **200 EMA/SMA States**: Indicates whether the price is above or below the key levels by using ⬆️ for an uptrend and ⬇️ for a downtrend.
- **Squeeze Momentum**: Highlights buy/sell opportunities using momentum and volatility analysis.

---

## Indicator Analysis

### 1. SMA/EMA Computation
   The 200-period SMA and EMA are calculated across multiple timeframes, providing a robust groundwork for multi-timeframe analysis.

### 2. Alligator Oscillator
   Utilizes the Smoothed Moving Average (SMMA) to plot Jaw, Teeth, and Lips curves offset to simulate the Alligator indicator.

### 3. Fractal Reversal
   Implements fractal detection using the Williams method:
   - Recognizes pivots in price structure.
   - Highlights points of potential trend reversals with arrows.

### 4. Squeeze Momentum
   Combines Bollinger Bands and Keltner Channels to identify when price volatility contracts. The indicator then detects the likely directional breakout by analyzing the momentum values.

---

## Usage

1. **Add the Script to TradingView**:  
   Copy and paste the Pine Script into TradingView's Pine Editor. Save and apply it to your chart.

2. **Configuration**:  
   - Customize parameters like SMA/EMA sources, Alligator line offsets, and Fractal strategies using the input fields built into the TradingView interface.
   - Set your desired Bollinger Band and Keltner Channel parameters within the Squeeze Momentum section.

3. **Interpret the Signals**:  
   - Use the information table to make informed decisions based on real-time multi-timeframe analysis.
   - Monitor the Alligator trend states and make use of the Stop-Loss levels calculated dynamically.

---

## Example Chart

Here’s an example of how the ARPS Info Table appears on a chart:

![ARPS Info Table Overview](https://via.placeholder.com/800x400?text=Chart+Example)

---

## Key Components

| Feature            | Functionality                                                                                 |
|--------------------|----------------------------------------------------------------------------------------------|
| **EMA/SMA Analysis** | Multiple crossovers across timeframes visualized clearly in the info table.                  |
| **Alligator Trends** | Easy visualization of bullish, neutral, and bearish trends using state conditions.            |
| **Squeeze Momentum** | Highlights potential breakout points during low-volatility moments.                          |
| **Fractal Detection** | Indicates significant price pivots and reversal opportunities.                             |
| **Stop-Loss Insight** | Calculates both long and short stop-loss prices with ATR for better risk management.        |

---

## Author

Developed by **Ali Rajabpour-Sanati**.  
For questions, feedback, or support, you can reach out via email: **ali.poursanati@gmail.com**

---

## License

This code is provided as-is and for educational purposes. Redistribution or modification is permitted with credit to the original author.

---
