# AC Trade Assistant

AC Trade Assistant is a speedy and compact forex trading tool developed by the Forex Robot Easy Team. This code serves as a sample implementation of the AC Trade Assistant tool.

## Input Parameters

The following input parameters can be defined:

- RiskPercent: The risk percentage per trade.
- FixedLots: The fixed lot size per trade.

## Order Types

The code defines two order types using an enum:

- ORDER_TYPE_BUY: Represents a buy order.
- ORDER_TYPE_SELL: Represents a sell order.

## Functions

### CalculateVolume

This function calculates the order volume based on the risk percent. It takes the account balance, stop loss, and risk percent as input parameters and returns the normalized volume.

### PlaceMarketOrder

This function is used to place a market order. It takes the symbol, order type, and volume as input parameters and returns a boolean value indicating whether the order was successfully placed or not.

### PlacePendingOrder

This function is used to place a pending order. It takes the symbol, order type, volume, and price as input parameters and returns a boolean value indicating whether the order was successfully placed or not.

## Start Program

The `OnStart` function is the entry point of the program. It performs the following steps:

1. Get the account balance.
2. Get the current market price.
3. Calculate the stop loss based on the risk percent.
4. Calculate the order volume based on the risk percent.
5. Place a market order with the calculated volume.
6. Place a pending order with the calculated volume and market price.
7. Check if both orders are successfully placed and print the corresponding message.

## Product Description

AC Trade Assistant is a speedy and compact forex trading tool designed to assist traders in managing their trades effectively. With the ability to calculate order volumes based on risk percentage and place market or pending orders, AC Trade Assistant simplifies the trading process and helps traders make informed decisions.

This code serves as a sample implementation of the AC Trade Assistant tool and showcases its functionality. Please note that ForexRobotEasy is not the official developer of this product. We only provide this code as a demonstration. For detailed reviews and trading results of the AC Trade Assistant, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/ac-trade-assistant-review-speedy-compact-forex-trading-tool/). To find the official developer of this product, please refer to the MQL5 platform.
