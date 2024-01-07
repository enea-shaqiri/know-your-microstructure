We implement the order flow imbalance (ofi) as defined in [The price impact of order book events](https://arxiv.org/pdf/1011.6402.pdf),
and try to reproduce the same results on Bitcoin data.  

The order flow imbalance is a real valued quantity that tries to capture the imbalance between supply and 
demand. The definition of ofi is based on first level orderbook data (increased volume and reduced volume).
Market orders are considered in the definition of ofi, but only implicitly, 
as they alter the length of either the bid queue or the ask queue.
The goal of the paper is to find a relationship between ofi and the price impact. This work adds to the literature on
price impact, but it is the first paper to consider orderbook events and contrary to the existing literature they
find a very simple relationship between ofi and price impact.

For a more in depth explanation check the paper or the report.

