# RSI Color Candles

This code is a custom indicator that colors candles based on the Relative Strength Index (RSI) level. It is intended to be used in forex trading and is provided by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product.

## Overview

The RSI Color Candles indicator calculates the RSI value and colors the candles based on whether the RSI is above or below a specified level. The RSI period and level are customizable inputs.

### Indicator Inputs

- RSI_Period: The period used to calculate the RSI value (default: 14)
- RSI_Level: The RSI level used for color coding (default: 50)

### Global Variables

- trade: Trade object
- rsi: RSI object

### Initialization

The expert initialization function (OnInit) initializes the RSI indicator with the specified symbol, timeframe, and RSI period.

### Tick Function

The expert tick function (OnTick) is called on every tick. It calculates the current RSI value and checks if it is above or below the specified RSI level. Based on the result, it calls the appropriate function to color the candles.

### Color Candles Functions

The ColorCandlesAboveLevel function colors the candles above the RSI level. You can place your custom code here to define the color or other properties of these candles.

The ColorCandlesBelowLevel function colors the candles below the RSI level. You can place your custom code here to define the color or other properties of these candles.

### Deinitialization

The expert deinitialization function (OnDeinit) is called when the expert is removed or the terminal is closed. You can perform any necessary deinitialization here.

### Custom Functions

The CustomFunction1 and CustomFunction2 functions are provided as placeholders for your custom code. You can place your own code in these functions to implement additional functionality.

### Custom Classes

The CustomClass1 and CustomClass2 classes are provided as placeholders for your custom classes. You can define your own classes here if needed.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - RSI Color Candles Review](https://forexroboteasy.com/forex-robot-review/rsi-color-candles-review-simplifying-forex-trading/). Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please use the MQL5 platform.
