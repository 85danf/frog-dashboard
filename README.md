$FROG Value
-----------------------


This is a simple scraper that scrapes Yahoo Finance for the price of $FROG and for the exchange rate of ILS/USD.
The Accompanying Grafana dashboard shows some relevant info:
 - The price change in $FROG (Although, admittedly you could just look it up on Yahoo)
 - based on the amount of shares you enter in the text box:
    - The total value of shares 
    - The value of shares after deducting the Capital Gains Tax (IL)
    - The total value of shares in NIS (based on the scraped exchange rate)
    - An approximation of total value in NIS after all deductions (exchange rates, commissions etc.)