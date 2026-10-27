# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T08:30:45Z**
- feed_generated_utc: 2026-10-27T08:30:49+00:00
- source_sha256: `91dd5cfe646d2167a44e186e551fad8e405feca0c6542fe509ae60f924cefec6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T08:30+00:00, close=79765.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026110|-5.32|112.62|-4.54|7778726|3.83|
|AAVE_USDT|130.950000|-4.22|-11.05|-3.44|24064139|0.76|
|PUMPFUN_USDT|0.004162|-3.83|-6.59|-3.05|21640669|2.40|
|DOT_USDT|0.992200|-2.97|-13.48|-2.19|10847264|2.02|
|FILECOIN_USDT|0.895900|-2.69|-11.47|-1.91|6145894|1.12|
|ONDO_USDT|0.407600|-2.67|-5.77|-1.89|23344262|2.45|
|AVAX_USDT|8.768000|-2.54|-8.30|-1.76|38087472|1.14|
|NEAR_USDT|4.457000|-2.53|-9.11|-1.75|95171750|2.24|
|ENA_USDT|0.205430|-2.34|9.31|-1.56|87193213|0.49|
|SILVER_USDT|52.990000|-2.28|-7.63|-1.50|258176772|1.89|
|INJ_USDT|7.758000|-2.21|-9.27|-1.43|23608806|2.58|
|WLD_USDT|0.435300|-2.17|-14.02|-1.39|68053483|2.30|
|PEPE_USDT|0.000004|-2.13|3.89|-1.35|62735158|0.23|
|TAO_USDT|248.230000|-2.08|-7.48|-1.30|46417268|1.21|
|SOL_USDT|99.840000|-1.96|-4.08|-1.18|716487806|1.00|
|ARB_USDT|0.166770|-1.89|-14.75|-1.11|20274985|1.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.950000|131.060000|130.950000|1.73|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.768000|8.733000|8.768000|1.26|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.992200|0.986400|0.992200|1.24|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.205430|0.206180|0.205430|2.63|Y|Y/N|N/N|Y|N|
|FILECOIN_USDT|0.895900|0.892900|0.895900|1.09|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.758000|7.725000|7.757000|1.14|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.026110|0.026120|0.026110|1.16|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.457000|4.405000|4.457000|1.95|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407600|0.406100|0.407600|1.19|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.35|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004162|0.004131|0.004162|1.50|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.990000|52.800000|52.990000|1.42|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.840000|99.380000|99.840000|0.99|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|248.230000|247.500000|248.230000|0.89|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435300|0.432500|0.435300|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T08:30:00+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=132.300000, depth_time=2026-10-27T08:30:11+00:00, book20_bid_proxy_usdt=523508, book20_ask_proxy_usdt=336255, funding_indicative=0.000076, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.22%, turnover=24064139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=8.828000, depth_time=2026-10-27T08:30:23+00:00, book20_bid_proxy_usdt=1119184, book20_ask_proxy_usdt=1868617, funding_indicative=-0.000066, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=38087472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T08:30:00+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=1.001200, depth_time=2026-10-27T08:30:15+00:00, book20_bid_proxy_usdt=307030, book20_ask_proxy_usdt=428910, funding_indicative=-0.000028, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=10847264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.208980, depth_time=2026-10-27T08:30:29+00:00, book20_bid_proxy_usdt=87412, book20_ask_proxy_usdt=150478, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=87193213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T08:30:00+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.903000, depth_time=2026-10-27T08:30:17+00:00, book20_bid_proxy_usdt=1014660, book20_ask_proxy_usdt=1280214, funding_indicative=0.000018, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=6145894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=7.851000, depth_time=2026-10-27T08:30:34+00:00, book20_bid_proxy_usdt=224258, book20_ask_proxy_usdt=249900, funding_indicative=0.000175, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=23608806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.029180, depth_time=2026-10-27T08:30:08+00:00, book20_bid_proxy_usdt=128360, book20_ask_proxy_usdt=97676, funding_indicative=-0.000771, next_funding_utc=2026-10-27T09:00:00+00:00, funding_cycle_h=1, 24h_change=-5.32%, turnover=7778726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=4.488000, depth_time=2026-10-27T08:30:26+00:00, book20_bid_proxy_usdt=2047754, book20_ask_proxy_usdt=4279786, funding_indicative=0.000067, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=95171750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.411600, depth_time=2026-10-27T08:30:21+00:00, book20_bid_proxy_usdt=1962584, book20_ask_proxy_usdt=3217507, funding_indicative=0.000038, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=23344262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.000004, depth_time=2026-10-27T08:30:39+00:00, book20_bid_proxy_usdt=117258, book20_ask_proxy_usdt=132751, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=62735158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T08:30:00+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.004216, depth_time=2026-10-27T08:30:13+00:00, book20_bid_proxy_usdt=1565779, book20_ask_proxy_usdt=2500180, funding_indicative=0.000042, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=21640669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=53.320000, depth_time=2026-10-27T08:30:31+00:00, book20_bid_proxy_usdt=38086608, book20_ask_proxy_usdt=47410848, funding_indicative=0.000080, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=258176772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=100.360000, depth_time=2026-10-27T08:30:44+00:00, book20_bid_proxy_usdt=18503348, book20_ask_proxy_usdt=12462545, funding_indicative=0.000053, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=716487806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=250.230000, depth_time=2026-10-27T08:30:42+00:00, book20_bid_proxy_usdt=103491, book20_ask_proxy_usdt=78626, funding_indicative=0.000043, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=46417268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T08:29:59+00:00, last15m_closed_end=2026-10-27T08:30+00:00, prior8high=0.439800, depth_time=2026-10-27T08:30:35+00:00, book20_bid_proxy_usdt=3231651, book20_ask_proxy_usdt=3865397, funding_indicative=-0.000209, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=68053483. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
