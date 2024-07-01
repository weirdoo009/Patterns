
---

# Stock Patterns Strategy

This TradingView Pine Script strategy identifies and trades based on ten different candlestick patterns. The script plots these patterns on the chart and generates buy and sell signals accordingly. The strategy includes a basic performance evaluation with stop loss and take profit mechanisms.

## Patterns Included

1. **Inside Bar**: When the high is lower than the previous high and the low is higher than the previous low.
2. **Bullish Engulfing**: When the current candle's close is higher than the open, and the previous candle's close is lower than its open, with the current candle fully engulfing the previous one.
3. **Bearish Engulfing**: When the current candle's close is lower than the open, and the previous candle's close is higher than its open, with the current candle fully engulfing the previous one.
4. **Shooting Star**: When the upper shadow (high minus max(open, close)) is more than twice the body (abs(open - close)) and the lower shadow (min(open, close) - low) is less than half the body.
5. **Hammer**: When the lower shadow (max(open, close) - low) is more than twice the body (abs(open - close)) and the upper shadow (high - min(open, close)) is less than half the body.
6. **Morning Star**: When there is a downtrend followed by a small-bodied candle and then a larger-bodied up candle.
7. **Evening Star**: When there is an uptrend followed by a small-bodied candle and then a larger-bodied down candle.
8. **Doji**: When the open and close prices are nearly equal, forming a cross or plus sign.
9. **Piercing Pattern**: When the close of a bearish candle is followed by a bullish candle that closes above the midpoint of the previous candle's body.
10. **Dark Cloud Cover**: When the close of a bullish candle is followed by a bearish candle that closes below the midpoint of the previous candle's body.

## How to Use

1. **Open TradingView**: Go to [TradingView](https://www.tradingview.com/).
2. **Open Pine Editor**: Open the Pine Script editor from the TradingView interface.
3. **Copy and Paste the Script**: Copy the entire Pine Script code and paste it into the Pine Script editor.
4. **Add to Chart**: Click on the "Add to Chart" button to see the script in action.


## How It Works

1. The script identifies various candlestick patterns and plots them on the chart.
2. It generates buy signals for Bullish Engulfing, Hammer, Morning Star, and Piercing Pattern.
3. It generates sell signals for Bearish Engulfing, Shooting Star, Evening Star, and Dark Cloud Cover.
4. The strategy includes stop loss and take profit levels for risk management.

## Customization

You can modify the script to adjust the patterns, entry rules, stop loss, and take profit levels to better fit your trading style.
