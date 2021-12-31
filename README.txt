MAR User Data

These are the csv files containing the raw data underlying most of the charts.
They are intended for user download.

Order-based exchanges: Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX
Level-book exchanges: Amex, NYSE
On May 1, 2017, MIDAS switched from the NYSE Ultra level-book feed to the NYSE Integrated Feed (NIF)

Exchanges denote trades against hidden orders: Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX, MIAX, MEMX
Exchanges do not denote trades against hidden orders: Amex, CHX (through November 4, 2019), NSX (through May 21, 2018), NYSE (through April, 2017)
Exchanges do not report trades against individual orders: Amex, NYSE (through April, 2017)

Notes:
1. In December 2013, the SIP began reporting odd lot trades. Beginning with January 2014, trades against hidden
orders and their associated volumes can be approximated as the difference between the total trades/volume reported to the SIP and
the total trades/volume reported on the direct (level-book) feeds for NYSE and Amex. 
2. Beginning May, 2017, NYSE hidden orders and odd lot trades are counted on the NIF.
3. Beginning April 9, 2018, NYSE reports all events for all symbols.
4. Beginning May 21, 2018, NSX reports trades against hidden orders.
5. Beginning November 4, 2019, CHX reports trades against hidden orders.

Trades, Trade Volume, Hidden, Hidden Volume, Odd Lots and Odd Lot Volume are counted/summed from the direct feeds for:
  Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX, MEMX, MIAX (& NYSE beginning May, 2017; & NSX beginning May 21, 2018 & CHX beginning November 4, 2019)
Trades, Trade Volume, Odd Lots and Odd Lot Volume are counted/summed from the direct feeds for:
  CHX, NSX
Trades, Trade Volume, Odd Lots and Odd Lot Volume are counted/summed from the SIP feeds for:
  Amex, NYSE (NYSE until April, 2017)
Hidden and Hidden Volume are computed as the difference between Trades/Trade Volume reported on the SIP feed and Trades/Trade Volume reported on the direct feeds for:
  Amex, NYSE (NYSE until April, 2017)
Hidden and Hidden Volume are not reported for:
  CHX (until November 4, 2019), NSX (until May 21, 2018)

For monthly (Date, Ticker, Exchange) data:
Trades: Count of all trade messages.
TradeVol('000): Sum of trade volume for all trade messages.
Cancels: Count of all cancel messages, either full or partial, for all exchanges.
Hidden: Count of trades against hidden orders from exchanges that report trades against hidden orders. Difference between SIP Trades and Direct Trades for NYSE and Amex.
LitTrades: Count of all trade messages for trades that are not against hidden orders. Computed as the difference between Trades and Hidden.
LitVol('000): Sum of trade volume for trades that are not against hidden orders. Computed as the difference between Trade Volume and Hidden Volume.
OrderVol('000): Sum of order volume for all add order messages.
TradesForHidden: Count of trades from exchanges that report trades against hidden orders.
HiddenVol('000): Sum of trade volume for trades against hidden orders from exchanges that report trades against hidden orders.
TradeVolForHidden('000): Sum of trade volume from exchanges that report trades against hidden orders.
OddLots: Count of odd lot trade messages for all exchanges.
OddLotVol('000): Sum of odd lot trade volume for all exchanges.

For quarterly (Date, Ticker) data:
TradesForOddLots = Trades: Count of trades from order-based exchanges.
TradeVolForOddLots('000) = TradeVol('000): Sum of trade volume from order-based exchanges.

The metrics:

Cancel-to-Trade = Cancels/LitTrades for Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX, MEMX, MIAX (& NYSE beginning May, 2017)
Trade-to-Order-Volume = 100*LitVol/OrderVol for All Exchanges
Hidden Rate = 100*Hidden/TradesForHidden for Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX, MEMX, MIAX (& Amex and NYSE from 2014)
Hidden Volume = 100*HiddenVol/TradeVolForHidden for Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX, MEMX, MIAX (& Amex and NYSE from 2014)
Oddlot Rate=100*OddLots/TradesForOddLots for Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX, MEMX, MIAX (& NYSE beginning May, 2017)
Oddlot Volume=100*OddLotVol/TradeVolForOddLots for Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX, MEMX, MIAX (& NYSE beginning May, 2017)
