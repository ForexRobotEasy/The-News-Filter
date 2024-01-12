# The News Filter ReadMe File

This ReadMe file provides an overview of the code for 'The News Filter' Expert Advisor developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. This ReadMe file only serves as a guide to understand the functionality of the code.

## Code Description

The code for 'The News Filter' Expert Advisor is written in MQL5 and consists of several functions. Here is a brief description of each function:

1. **OnInit()**: This function is called during the initialization of the Expert Advisor. Currently, there is no specific initialization code implemented.

2. **OnDeinit(const int reason)**: This function is called during the deinitialization of the Expert Advisor. Currently, there is no specific deinitialization code implemented.

3. **OnTick()**: This function is called on each tick of the price data. Currently, there is no specific tick function code implemented.

4. **IsNewsTime()**: This function is used to determine if it is news time or not. The code to determine news time is not implemented and currently returns false.

5. **ManageOrders()**: This function is responsible for managing open positions and pending orders. The code to manage orders is not implemented.

6. **SelectNewsSource()**: This function is used to select and refresh the news source. The code to select and refresh the news source is not implemented.

7. **FilterNews()**: This function is responsible for filtering news based on user preferences. The code to filter news is not implemented.

8. **ManageOrderChoices()**: This function is used to handle order management choices. The code to handle order management choices is not implemented.

9. **OnStart()**: This is the main entry point of the Expert Advisor. It contains a while loop that checks if it is news time, and if so, it calls the functions to manage orders, select news source, filter news, and manage order choices. The loop sleeps for the refresh interval specified in minutes.

## Product Description

'The News Filter' is an Expert Advisor developed by the Forex Robot Easy Team. It aims to optimize forex trading during news time by filtering out expert advisors and manual charts. This Expert Advisor helps traders avoid potential market volatility and unpredictable price movements during news events.

Product Features:

- News filtering: The Expert Advisor filters out expert advisors and manual charts during news time to avoid trading during volatile market conditions.

- Customizable preferences: Traders can customize their news filtering preferences based on their individual trading strategies.

For detailed reviews and trading results of 'The News Filter' product, please visit the [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/the-news-filter-review-optimize-forex-trading-during-news-time/) website.

Please note that ForexRobotEasy is not the official developer of this product. This ReadMe file provides a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.
