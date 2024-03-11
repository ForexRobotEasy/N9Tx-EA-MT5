# N9Tx EA MT5

Developer's site: [forexroboteasy.com](https://forexroboteasy.com)

Developed by: Forex Robot Easy Team

---

## Description

The N9Tx EA MT5 is an expert advisor (EA) for trading in the forex market. It is designed to implement a combination of trading strategies, including the central strategy derived from PROscalper, as well as supplementing it with TrendFollowerSR and DailyBreakouts strategies.

This EA opens and closes positions based on the implemented strategies and uses a fixed stop loss and take profit for each position. The stop loss is set at 50 pips, while the take profit is set at 100 pips.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

---

## How it Works

The EA follows the logic outlined below:

1. The `OnTick()` function is the entry point of the EA for trading. It retrieves the current market prices and checks if a new trade can be opened based on the `IsTradeAllowed()` function.

2. The `IsTradeAllowed()` function checks if trading is allowed based on certain conditions. You can add your own conditions here. If trading is allowed, the function returns `true`; otherwise, it returns `false`.

3. If trading is allowed, the EA calls the `OpenPositions()` and `ClosePositions()` functions.

4. The `OpenPositions()` function implements the central strategy derived from PROscalper and supplements it with TrendFollowerSR and DailyBreakouts strategies. You can add your own implementation of these strategies here.

5. The `ClosePositions()` function checks if any open positions need to be closed based on the stop loss and take profit levels. You can add your own logic here to close positions based on these levels.

---

For detailed reviews and trading results of this product, visit the [official product review](https://forexroboteasy.com/forex-robot-review/n9tx-ea-mt5-review-innovative-night-scalping-forex-tool/).

Please note that ForexRobotEasy is not the official developer of this product. We only show sample code that can work as described in this product. To find the official developer of this product, use MQL5.
