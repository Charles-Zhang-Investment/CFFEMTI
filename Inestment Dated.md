# Investment Dated

Unsorted notes. The most useful aspects are "observations": facts, trends, phenomenon that we keep a note of.
Likely belong to either QuantStrategy2023, CFFEMTI, or pending migration of Investment/Wiki notes from work.

## 20231228

### Investment Notes Ideas

* (Resources) AQR Capital Momentum trading published papers (Dildar knows a lot on this)
* (Practice, #20231216, !Todo) Find next top 10, buy and hold $1000, prepare a spreadsheet to do bookkeeping for now. Our current strategy is buy and hold 1yr never sell except when making big gains. Risk aversion that is. In general, we just never sell. The difference from previous naive approach is we are NOT selling immediately it hits +0%, rather holding either it's high enough percentage gain, or its 1yr. ¶Notice the behavior is well defined, and we should look up the latest top 10 movers over the past 15 days before making buy/sell orders.

Terms to collect (can collect to todo list):

* Seagul spread
* Cholesky Decomposition
* Pair trading strategy: correlation

## 20240102

### (Observation) Monte Carlo for Risk Simulation

Tags: Observation

Simulation must be done in return space otherwise the output distribution might be meaningless. E.g. when considered in returns, both SPX and AAPL looks like some sort of very thin normal distribution, and the simulation outcome from this is normal distribution as well.

When not using return space as input, output can seem random or uniform. This is what happened with Ray's https://finrisk.streamlit.app/ in Nov 2023.

Notice the fact that interest rate, and other rates' returns follow a (even if skewed tail) normal-like distribution is SURPRISING fact: "The normal distribution is a key element to modern portfolio theory, a mathematical approach to investing that assumes that certain returns will follow a normal distribution." (https://www.investopedia.com/articles/investing/100714/using-normal-distribution-formula-optimize-your-portfolio.asp)