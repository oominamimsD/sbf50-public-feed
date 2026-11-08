# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T14:30:39Z**
- feed_generated_utc: 2026-11-08T14:30:41+00:00
- source_sha256: `fd80fef34c011ea3a8d653a12c579663a34f76a7844a6027c2c4c1a5ce700209`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T14:30+00:00, close=75915.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T14:00+00:00, close=75895.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001832|-10.04|56.03|-10.31|23088165|0.55|
|AKE_USDT|0.005428|-9.27|-51.26|-9.54|26849261|1.84|
|IDOL_USDT|0.030220|-9.24|72.47|-9.51|15755314|4.29|
|TIA_USDT|0.420400|-4.80|-14.22|-5.07|7130563|2.38|
|WLD_USDT|0.325100|-3.12|-19.60|-3.39|24892482|3.08|
|ENA_USDT|0.153920|-2.69|-20.66|-2.96|29526576|0.65|
|AAVE_USDT|128.900000|-2.51|-4.87|-2.78|9650112|0.78|
|LINK_USDT|10.723000|-1.11|-7.32|-1.38|61395132|0.93|
|SUI_USDT|0.848100|-1.05|-5.97|-1.32|24146863|1.18|
|ONDO_USDT|0.359300|-1.04|-12.87|-1.31|7368433|2.78|
|ADA_USDT|0.179800|-0.99|-7.12|-1.26|10642065|5.56|
|DOGE_USDT|0.070940|-0.89|-6.21|-1.16|43986862|1.41|
|INJ_USDT|8.053000|-0.75|7.57|-1.02|19000008|1.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|128.900000|128.580000|128.900000|1.43|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179800|0.179300|0.179700|1.84|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005428|0.005312|0.005428|0.82|N|Y/N|N/N|Y|N|
|DOGE_USDT|0.070940|0.071040|0.070940|3.57|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.153920|0.152800|0.153710|0.84|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030220|0.028891|0.030215|1.87|N|Y/Y|N/N|Y|N|
|INJ_USDT|8.053000|8.089000|8.053000|2.98|Y|Y/Y|N/N|Y|N|
|LINK_USDT|10.723000|10.691000|10.723000|1.04|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359300|0.359600|0.359300|1.24|N|Y/N|Y/Y|Y|N|
|ONE_USDT|0.001832|0.001820|0.001832|0.29|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.848100|0.846300|0.847800|2.51|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.420400|0.419200|0.420400|0.93|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.325100|0.323900|0.325100|2.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=131.400000, depth_time=2026-11-08T14:30:22+00:00, book20_bid_proxy_usdt=312538, book20_ask_proxy_usdt=386872, funding_indicative=0.000066, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=9650112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.181200, depth_time=2026-11-08T14:30:33+00:00, book20_bid_proxy_usdt=9346015, book20_ask_proxy_usdt=10000268, funding_indicative=-0.000035, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=10642065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.005684, depth_time=2026-11-08T14:30:09+00:00, book20_bid_proxy_usdt=47301, book20_ask_proxy_usdt=34873, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=26849261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.071640, depth_time=2026-11-08T14:30:34+00:00, book20_bid_proxy_usdt=4405021, book20_ask_proxy_usdt=4670148, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=43986862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.155690, depth_time=2026-11-08T14:30:19+00:00, book20_bid_proxy_usdt=189242, book20_ask_proxy_usdt=209940, funding_indicative=-0.000112, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=29526576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.031950, depth_time=2026-11-08T14:30:12+00:00, book20_bid_proxy_usdt=4552, book20_ask_proxy_usdt=4585, funding_indicative=0.000923, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.24%, turnover=15755314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=8.174000, depth_time=2026-11-08T14:30:36+00:00, book20_bid_proxy_usdt=169033, book20_ask_proxy_usdt=389154, funding_indicative=0.000261, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=19000008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=10.788000, depth_time=2026-11-08T14:30:24+00:00, book20_bid_proxy_usdt=466414, book20_ask_proxy_usdt=927529, funding_indicative=0.000001, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=61395132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.365700, depth_time=2026-11-08T14:30:25+00:00, book20_bid_proxy_usdt=2007479, book20_ask_proxy_usdt=1549780, funding_indicative=0.000031, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=7368433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.001923, depth_time=2026-11-08T14:30:07+00:00, book20_bid_proxy_usdt=14134, book20_ask_proxy_usdt=10529, funding_indicative=-0.000783, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.04%, turnover=23088165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.859000, depth_time=2026-11-08T14:30:27+00:00, book20_bid_proxy_usdt=1582628, book20_ask_proxy_usdt=2223077, funding_indicative=0.000039, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=24146863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.425500, depth_time=2026-11-08T14:30:12+00:00, book20_bid_proxy_usdt=284037, book20_ask_proxy_usdt=384666, funding_indicative=-0.000021, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=7130563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T14:30:02+00:00, last15m_closed_end=2026-11-08T14:30+00:00, prior8high=0.328300, depth_time=2026-11-08T14:30:15+00:00, book20_bid_proxy_usdt=3369183, book20_ask_proxy_usdt=3451835, funding_indicative=-0.000069, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=24892482. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
