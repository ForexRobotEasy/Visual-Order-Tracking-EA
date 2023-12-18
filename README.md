# Visual Order Tracking EA ReadMe

This ReadMe file provides details about the Visual Order Tracking EA code. It explains the functions, global variables, and how the EA works. Please note that Forex Robot Easy Team is not the official developer of this product. The code provided here is a sample that can work as described in the product.

## Function Declarations

The following functions are declared in the code:

1. `int OnInit()`: Initializes the VOT EA and sets up chart settings.
2. `void OnDeinit(const int reason)`: Deinitializes the VOT EA and cleans up any resources.
3. `void OnTick()`: Updates the VOT EA on each tick.
4. `void OnChartEvent(const int id, const long& lparam, const double& dparam, const string& sparam)`: Handles chart events.
5. `string FormatTradeResult(double pips, double profit, double profit_percentage, double percentage_change)`: Formats the trade result with the specified values.

## Global Variables

The following global variables are used in the code:

1. `color profitableBuyColor = Lime`: Color for profitable buy positions.
2. `color losingBuyColor = Red`: Color for losing buy positions.
3. `color profitableSellColor = DodgerBlue`: Color for profitable sell positions.
4. `color losingSellColor = DarkOrange`: Color for losing sell positions.
5. `color lineColor = Gray`: Color for lines.

## OnInit Function

The `OnInit` function is called during the initialization of the EA. It initializes the VOT EA and sets up chart settings. In this code, it enables the display of trade levels and object descriptions on the chart.

## OnDeinit Function

The `OnDeinit` function is called when the EA is deinitialized. It cleans up any resources used by the VOT EA. In this code, it disables the display of trade levels and object descriptions on the chart.

## OnTick Function

The `OnTick` function is called on each tick to update the VOT EA. This function can be customized to perform specific actions or calculations based on market conditions.

## OnChartEvent Function

The `OnChartEvent` function is called when a chart event occurs. It can be used to handle specific chart events and perform corresponding actions.

## FormatTradeResult Function

The `FormatTradeResult` function formats the trade result with the specified values. It takes the number of pips, profit, profit percentage, and percentage change as parameters and returns a formatted string.

Please note that this code is a sample and may require modifications to work in your specific trading environment.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Visual Order Tracking EA Review](https://forexroboteasy.com/forex-robot-review/visual-order-tracking-ea-review-enhancing-forex-trade-visualization/).
