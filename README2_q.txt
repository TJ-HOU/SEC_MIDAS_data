MAR User Data

These are the csv files containing the raw data underlying most of the charts.
They are intended for user download.

Exchanges denote trades against hidden orders: Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX
Exchanges do not denote trades against hidden orders: Amex, CHX, NSX, NYSE
Exchanges do not report trades against individual orders: Amex, NYSE

Note: In December 2013, the SIP began reporting odd lot trades. Beginning with January 2014, trades against hiddden
orders and their associated volumes can be computed as the difference between the total trades/volume reported to the SIP and
the total trades/volume reported on the direct feeds for NYSE and Amex.

LitVol('000): Sum of trade volume for trades that are not against hidden orders.
OrderVol('000): Sum of order volume for all add order messages.
Hidden: Count of trades against hidden orders from exchanges that report trades against hidden orders.
TradesForHidden: Count of trades from exchanges that report trades against hidden orders.
HiddenVol('000): Sum of trade volume for trades against hidden orders from exchanges that report trades against hidden orders.
TradeVolForHidden('000): Sum of trade volume from exchanges that report trades against hidden orders.
Cancels: Count of all cancel messages, either full or partial, for all exchanges.
LitTrades: Count of all trade messages for trades that are not against hidden orders.
OddLots: Count of odd lot trade messages for all exchanges.
TradesForOddLots: Count of trades from exchanges that report individual trades.
OddLotVol('000): Sum of odd lot trade volume for all exchanges.
TradeVolForOddLots('000): Sum of trade volume from exchanges that report individual trades.

The metrics:

Cancel-to-Trade = Cancels/LitTrades for Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX
Trade-to-Order-Volume = 100*LitVol/OrderVol for All Exchanges
Hidden Rate = 100*Hidden/TradesForHidden for Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX
Hidden Volume = 100*HiddenVol/TradeVolForHidden for Arca, Bats-Y, Bats-Z, Boston, Edga-A, Edge-X, Nasdaq, PHLX
Oddlot Rate=100*OddLots/TradesForOddLots for Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX
Oddlot Volume=100*OddLotVol/TradeVolForOddLots for Arca, Bats-Y, Bats-Z, Boston, CHX, Edga-A, Edge-X, Nasdaq, NSX, PHLX
