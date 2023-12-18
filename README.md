# Classic Lock MT4 - Forex Trading System

This is a forex trading system called Classic Lock MT4. It is developed by Forex Robot Easy Team and can be found on their website [here](https://forexroboteasy.com/forex-robot-review/classic-lock-mt4-review-versatile-forex-trading-system/). Please note that ForexRobotEasy is not the official developer of this product, but we are providing a sample code that can work as described in this product.

## Description

Classic Lock MT4 is a versatile forex trading system that aims to open buy or sell orders based on certain conditions. The system works on the MetaTrader 4 platform and requires the Trade and PositionInfo libraries to be imported.

The system allows you to define a specific timeframe for the strategy and a magic number for identification of the orders. It then loops through all available symbols and checks if trading is allowed for each symbol. If the symbol is a currency pair, it gets the current price and opens a buy order if the price is above a certain threshold, or a sell order if the price is below the threshold.

The system provides feedback through the Print function, indicating whether the order was successfully opened or not. It also includes functions for initialization, starting the expert advisor, and deactivating the expert advisor.

## How it Works

1. The system first imports the necessary libraries for trading and position information.
2. It defines global variables, including the desired timeframe for the strategy and a magic number for order identification.
3. The main function, ClassicLockMT4, is defined. It gets the current timeframe and checks if it matches the required timeframe for the strategy.
4. If the timeframes match, the function loops through all available symbols.
5. For each symbol, it checks if trading is allowed and if it is a currency pair.
6. If both conditions are met, it gets the current price and checks if it is above or below the threshold (in this case, 1.0).
7. If the price is above the threshold, a buy order is opened with a specified volume.
8. If the price is below the threshold, a sell order is opened with the same volume.
9. The function provides feedback through the Print function, indicating whether the order was successfully opened or not.
10. The OnInit function is used to set the required timeframe for the strategy.
11. The OnTick function is used to start the expert advisor and call the ClassicLockMT4 function.
12. The OnDeinit function is used to print a message indicating that the expert advisor has been deactivated.

## Product Description

Classic Lock MT4 is a versatile forex trading system developed by the Forex Robot Easy Team. It is designed to open buy or sell orders based on specific conditions. This system is compatible with the MetaTrader 4 platform and requires the Trade and PositionInfo libraries to be imported.

To use this system, you need to define the desired timeframe for the strategy and a magic number for order identification. The system will then loop through all available symbols, checking if trading is allowed for each symbol. If the symbol is a currency pair, it will open a buy order if the price is above a certain threshold, or a sell order if the price is below the threshold.

The system provides feedback through the Print function, indicating whether the order was successfully opened or not. This allows you to monitor the system's performance and make necessary adjustments.

Please note that ForexRobotEasy is not the official developer of this product. We are providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5, the official platform for MetaTrader programming.

For detailed reviews and trading results of this product, you can visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/classic-lock-mt4-review-versatile-forex-trading-system/).
