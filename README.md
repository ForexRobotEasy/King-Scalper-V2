# King Scalper V2

King Scalper V2 is an advanced Forex trading robot developed by the Forex Robot Easy Team. This EA is designed to optimize Forex trades with its advanced features. 

For detailed reviews and trading results of this product, please visit our website: [King Scalper V2 Review - Optimizing Forex Trades with Advanced Features](https://forexroboteasy.com/forex-robot-review/king-scalper-v2-review-optimizing-forex-trades-with-advanced-features/)

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Trading Functions

### EA Option: Calculate Lot Size, Max Lot, and Auto Mode Balance

```c++
double CalculateLotSize(double balance, double riskPercentage)
```

This function calculates the lot size based on the user's balance and risk percentage. The calculated lot size is returned.

### MM Zone A: Optimizing Trades with Balance Percentage

#### SetTakeProfit

```c++
void SetTakeProfit(double takeProfit)
```

This function sets the take profit for buy and sell orders. The specified take profit value is used to optimize trades.

#### CloseAllTradesByPercentage

```c++
void CloseAllTradesByPercentage(double balancePercentage)
```

This function closes all trades based on a specific percentage of the user's balance. It helps in optimizing trades by closing them when the balance reaches a certain threshold.

### MM Zone B: Trade Management with Set Amounts

```c++
void TradeManagementWithSetAmount(double amount)
```

This function manages trades using the specified amount. It provides trade management capabilities by adjusting the trade parameters based on the specified amount.

## Main Functions

### OnInit

```c++
int OnInit()
```

This function initializes the King Scalper V2 EA. It performs the necessary setup and initialization tasks before starting the trading operations.

### OnTick

```c++
void OnTick()
```

This function is called on every tick and performs the trading operations based on the developed functions. It executes the trading strategy and manages open trades.

### OnDeinit

```c++
void OnDeinit(const int reason)
```

This function deinitializes the King Scalper V2 EA. It performs the necessary cleanup tasks before stopping the EA.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of King Scalper V2. We are only showcasing a sample code that can work as described in this product. To find the official developer of King Scalper V2, please use MQL5.
