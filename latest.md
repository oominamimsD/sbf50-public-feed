# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T21:30:28Z**
- feed_generated_utc: 2026-11-07T21:30:29+00:00
- source_sha256: `1747e792129fe3e3c74a8e3827af74459d1c97eba9e76607c515571955e6420c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T21:30+00:00, close=75603, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T21:00+00:00, close=75657.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.121200|-2.57|-60.99|-2.41|11210142|8.25|
|AAVE_USDT|129.370000|-2.16|-4.53|-2.00|8978609|0.77|
|WLD_USDT|0.329100|-1.93|-18.62|-1.77|25837250|3.04|
|TIA_USDT|0.434400|-1.63|-11.36|-1.47|6636122|2.30|
|PEPE_USDT|0.000005|-1.34|-3.02|-1.18|44718635|0.21|
|DOT_USDT|0.882100|-1.32|-8.01|-1.16|5716992|1.13|
|NEAR_USDT|3.633000|-1.25|-18.83|-1.09|24133107|2.75|
|ENA_USDT|0.156210|-1.24|-19.48|-1.08|27550490|0.64|
|ZEC_USDT|1242.970000|-1.17|-3.23|-1.01|1832150561|0.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.370000|129.250000|129.370000|1.22|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.882100|0.884000|0.882100|4.55|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.156210|0.156150|0.156210|0.38|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.633000|3.620000|3.633000|0.95|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.72|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.434400|0.434600|0.434300|3.24|Y|Y/N|N/N|Y|N|
|UAI_USDT|0.121200|0.121100|0.121100|0.63|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329100|0.327700|0.329100|0.81|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1242.970000|1235.840000|1242.970000|1.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=131.750000, depth_time=2026-11-07T21:30:09+00:00, book20_bid_proxy_usdt=373924, book20_ask_proxy_usdt=403709, funding_indicative=0.000041, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=8978609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=0.900300, depth_time=2026-11-07T21:30:19+00:00, book20_bid_proxy_usdt=282130, book20_ask_proxy_usdt=322759, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=5716992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=0.157740, depth_time=2026-11-07T21:30:23+00:00, book20_bid_proxy_usdt=294451, book20_ask_proxy_usdt=115490, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=27550490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=3.667000, depth_time=2026-11-07T21:30:21+00:00, book20_bid_proxy_usdt=3643746, book20_ask_proxy_usdt=4637431, funding_indicative=0.000042, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=24133107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=0.000005, depth_time=2026-11-07T21:30:16+00:00, book20_bid_proxy_usdt=59403, book20_ask_proxy_usdt=36085, funding_indicative=0.000045, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=44718635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=0.443000, depth_time=2026-11-07T21:30:12+00:00, book20_bid_proxy_usdt=361621, book20_ask_proxy_usdt=303641, funding_indicative=0.000018, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=6636122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=0.124500, depth_time=2026-11-07T21:30:07+00:00, book20_bid_proxy_usdt=221748, book20_ask_proxy_usdt=165766, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=11210142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=0.335000, depth_time=2026-11-07T21:30:10+00:00, book20_bid_proxy_usdt=4271484, book20_ask_proxy_usdt=3564273, funding_indicative=-0.000195, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=25837250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T21:30:01+00:00, last15m_closed_end=2026-11-07T21:30+00:00, prior8high=1268.400000, depth_time=2026-11-07T21:30:27+00:00, book20_bid_proxy_usdt=430592, book20_ask_proxy_usdt=176234, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=1832150561. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
