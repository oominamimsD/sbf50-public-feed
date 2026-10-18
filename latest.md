# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T11:15:37Z**
- feed_generated_utc: 2026-10-18T11:15:39+00:00
- source_sha256: `86d0f66e9ea0487c7132834af3e9f0bd2111d81802ce7e65275ccee0a5725a3a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T11:15+00:00, close=82068.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T11:00+00:00, close=82060.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062170|-6.01|-33.45|-6.93|14905154|1.61|
|EIGEN_USDT|0.242500|-5.38|2.92|-6.30|6441665|4.12|
|SAND_USDT|0.061260|-2.82|-8.96|-3.74|47041290|1.63|
|FILECOIN_USDT|1.056900|-2.80|-6.28|-3.72|18002481|0.95|
|PUMPFUN_USDT|0.004289|-2.78|-25.08|-3.70|23066085|2.33|
|ZRO_USDT|1.842600|-2.26|-8.80|-3.18|6543656|0.54|
|TIA_USDT|0.644000|-2.12|25.53|-3.04|58303918|6.21|
|XPL_USDT|0.078580|-1.93|-9.42|-2.85|5826363|1.27|
|OP_USDT|0.126760|-1.73|-8.50|-2.65|8675784|1.58|
|ZEC_USDT|1126.810000|-1.27|-8.52|-2.19|1198216772|0.09|
|DOT_USDT|1.105800|-1.03|-12.02|-1.95|16663606|0.90|
|ICP_USDT|2.904000|-0.81|-7.78|-1.73|6003669|3.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.105800|1.101900|1.106100|1.87|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.242500|0.243800|0.242500|3.18|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.056900|1.048800|1.056900|0.55|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.904000|2.897000|2.906000|2.28|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126760|0.126170|0.126760|2.04|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004289|0.004272|0.004289|4.12|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.061260|0.060750|0.061260|0.11|N|Y/N|N/N|Y|N|
|STRK_USDT|0.062170|0.061570|0.062170|1.13|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.644000|0.640300|0.644500|2.20|N|Y/N|Y/Y|Y|N|
|XPL_USDT|0.078580|0.078080|0.078610|1.27|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1126.810000|1124.590000|1127.170000|1.40|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.842600|1.832300|1.842600|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=1.120400, depth_time=2026-10-18T11:15:33+00:00, book20_bid_proxy_usdt=381457, book20_ask_proxy_usdt=223987, funding_indicative=-0.000089, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=16663606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T11:15:02+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.249900, depth_time=2026-10-18T11:15:10+00:00, book20_bid_proxy_usdt=789950, book20_ask_proxy_usdt=537378, funding_indicative=-0.000010, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.38%, turnover=6441665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=1.069800, depth_time=2026-10-18T11:15:15+00:00, book20_bid_proxy_usdt=642139, book20_ask_proxy_usdt=662299, funding_indicative=-0.000001, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=18002481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T11:15:02+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=2.941000, depth_time=2026-10-18T11:15:35+00:00, book20_bid_proxy_usdt=1036707, book20_ask_proxy_usdt=892367, funding_indicative=0.000020, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=6003669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.128100, depth_time=2026-10-18T11:15:29+00:00, book20_bid_proxy_usdt=105926, book20_ask_proxy_usdt=61214, funding_indicative=-0.000225, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=8675784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.004347, depth_time=2026-10-18T11:15:18+00:00, book20_bid_proxy_usdt=2245628, book20_ask_proxy_usdt=1173055, funding_indicative=0.000044, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=23066085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.063330, depth_time=2026-10-18T11:15:13+00:00, book20_bid_proxy_usdt=486443, book20_ask_proxy_usdt=499953, funding_indicative=-0.006488, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=47041290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.064850, depth_time=2026-10-18T11:15:08+00:00, book20_bid_proxy_usdt=320166, book20_ask_proxy_usdt=396088, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=14905154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.665300, depth_time=2026-10-18T11:15:23+00:00, book20_bid_proxy_usdt=178638, book20_ask_proxy_usdt=138571, funding_indicative=-0.000056, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=58303918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T11:15:02+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=0.079080, depth_time=2026-10-18T11:15:25+00:00, book20_bid_proxy_usdt=455859, book20_ask_proxy_usdt=405805, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=5826363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T11:15:01+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=1143.000000, depth_time=2026-10-18T11:15:30+00:00, book20_bid_proxy_usdt=352644, book20_ask_proxy_usdt=871570, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=1198216772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T11:15:02+00:00, last15m_closed_end=2026-10-18T11:15+00:00, prior8high=1.874500, depth_time=2026-10-18T11:15:21+00:00, book20_bid_proxy_usdt=66957, book20_ask_proxy_usdt=35891, funding_indicative=-0.000020, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=6543656. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
