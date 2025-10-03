Python Backtesting Engine!!!


Data from: https://app.alpaca.markets/brokerage/new-account

This will be a CSV-backed engine, no sql database

This project is still in progress. While the backtesting engine works, the post-trade analytics tool is still in the process of being developed.
Since the code is incomplete, running the code will return errors.

Target to finish the analytics tool by 10th Oct



IMPORTANT!!!!!!!!!
______________________
Must remember to make it such that all positions are closed at final price once trade session ends



Planned update path / feasible stock trading strategies (this is PRIVATE!):
https://docs.google.com/document/d/1gL_6qlcGeiDzzHlxFqGG686iXOYxIAoqoXFa4ODVVAw/edit?tab=t.0


Notes:
Algorithm is allowed to purchase/sell stock at any price between the range of high and low. However, it cannot make this decision based on price information.
    This means that the algorithm is not allowed to "know" the high and low prices, thus can only make decisions in a "hit-or-miss" manner. E.g. algorithm cannot choose to buy where price = row["Low"], but can make a decision like buy where price = 98%(Open).


_____________________________

For any enquiries feel free to reach out to me at limky42710@gmail.com
