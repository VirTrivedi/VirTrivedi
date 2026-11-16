### Hi, I'm Vir

Finance + CS & Math at the University of Maryland ('27). I build market data infrastructure and study market microstructure. I'm currently a software engineering intern at Trillium Surveyor, working on cross-asset market data for manipulation detection.

**Research**
- [Order Book Imbalance Predictability](https://github.com/VirTrivedi/Order-Book-Imbalance): a 22-page paper on full-depth NASDAQ data. Imbalance predicts 10 ms mid-price moves with an information coefficient above 0.28, and the signal fades with horizon.
- [American Option Methods](https://github.com/VirTrivedi/American-Option-Methods): binomial tree, Crank-Nicolson PDE and Longstaff-Schwartz pricers with discrete dividends, checked against WRDS OptionMetrics quotes.

**Trading systems (C++)**
- [Fill-Simulator](https://github.com/VirTrivedi/Fill-Simulator): an event-driven backtester with per-level FIFO queues and latency modeling. Its strategy parameters are tuned by [Optimal-Edge-Fitter](https://github.com/VirTrivedi/Optimal-Edge-Fitter).
- [Market-Data-Processing](https://github.com/VirTrivedi/Market-Data-Processing): NASDAQ/BATS full-depth parsers, multi-venue merged books, bars and correlations. The PCAP-to-order-book step runs on AWS through [Backtesting-Airflow](https://github.com/VirTrivedi/Backtesting-Airflow).
- [Simple-Matching-Engine](https://github.com/VirTrivedi/Simple-Matching-Engine): a small exchange simulator with price-time matching over TCP, top-of-book over UDP multicast and drop-copy reports.

**Tools:** C++17 · Python · SQL · NumPy/pandas/statsmodels · PyTorch · AWS · Airflow · Linux

📫 [LinkedIn](https://www.linkedin.com/in/vir-trivedi/)
