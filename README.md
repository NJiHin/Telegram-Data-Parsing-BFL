# Telegram Data Parsing Script for "Binance Future Liquidations"
Extracts Data from "Binance Future Liquidations" Telegram chat history and plots charts on BTC liquidation prices
Binance Futures Liquidations Telegram Chat Link: https://t.me/BinanceLiquidations

# Why?
At first I joined the Telegram Chat to gain more information as I was doing some Crypto Trading on the side. As time went on I noticed the sheer amount of data that was flowing in from this chat and wanted to filter this data. This idea evolved and soon I decided I wanted to plot the liquidated prices for BTC/USDT and perhaps see if there is anything interesting I could deduce from it.

# Visualised Data
The end product is a script that plots a line graph of the Liquidation Prices for BTC against the liquidated amont in USDT with a colored dot indicating whether it is a Liquidated Short or Liquidated Long. 

The code can be easily edited if the user wants to view other coin pairs. The code also filters out all other messages that the channel sends, such as advertisments, as well as Telegram alerts, such as if the admin of the channel pins the message.

# Conclusion
Does this chart provide any useful information? Probably not, but it was fun project to get more experince with data parsing and MatPLotLib Python Library.
