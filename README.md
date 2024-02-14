# Fight Club GBPUSD ReadMe File

## Developer's Site
Forex Robot Easy Team
[forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/fight-club-gbpusd-review-proven-forex-software-for-smart-trading/)

**Note:** ForexRobotEasy is not the official developer of this product. We only show sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Overview
The Fight Club GBPUSD is an expert advisor (EA) designed for trading the GBP/USD currency pair. It uses a trend-following strategy to open long or short trades based on the direction of the trend. The EA calculates the stop loss, take profit, and lot size based on a specified risk level.

## Input Parameters
- RiskLevel: Risk level for each trade (default: 1.0)

## Global Variables
- StopLoss: Calculated stop loss value
- TakeProfit: Calculated take profit value
- LotSize: Calculated lot size based on risk level and account balance

## Initialization Function (OnInit)
The OnInit function is called during the initialization phase of the EA. It calculates the stop loss, take profit, and lot size based on the specified risk level and account balance.

## Start Function (OnTick)
The OnTick function is called on each tick of the price. It determines the trend direction using a moving average crossover strategy. If the trend is positive, a long trade is opened. If the trend is negative, a short trade is opened.

## Deinitialization Function (OnDeinit)
The OnDeinit function is called when the EA is being shut down. It closes all open trades for the current symbol.

## Backlink
For detailed reviews and trading results of this product, please visit:
[forexroboteasy.com/forex-robot-review/fight-club-gbpusd-review-proven-forex-software-for-smart-trading/](https://forexroboteasy.com/forex-robot-review/fight-club-gbpusd-review-proven-forex-software-for-smart-trading/)
