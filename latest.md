# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T21:45:20Z**
- feed_generated_utc: 2026-11-07T21:45:22+00:00
- source_sha256: `9bf2846c5709a1186b905f2abcb3e5766e23113475ebd77689b72bf6146c0279`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T21:45+00:00, close=75671.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T21:00+00:00, close=75657.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.121000|-2.73|-61.05|-2.66|11254516|8.27|
|AAVE_USDT|129.790000|-1.84|-4.22|-1.77|9048165|0.77|
|WLD_USDT|0.330700|-1.46|-18.22|-1.39|26119297|3.02|
|TIA_USDT|0.435800|-1.31|-11.07|-1.24|6745117|2.29|
|PEPE_USDT|0.000005|-1.30|-2.98|-1.23|45134051|1.66|
|QNT_USDT|196.520000|-1.17|-2.25|-1.10|42949885|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.790000|129.130000|129.790000|0.89|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.72|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.520000|196.250000|196.520000|1.33|N|N/N|N/N|Y|N|
|TIA_USDT|0.435800|0.434300|0.435900|1.73|N|Y/N|N/N|Y|N|
|UAI_USDT|0.121000|0.120700|0.121000|0.82|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.330700|0.327700|0.330700|1.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T21:45:01+00:00, last15m_closed_end=2026-11-07T21:45+00:00, prior8high=131.600000, depth_time=2026-11-07T21:45:10+00:00, book20_bid_proxy_usdt=392986, book20_ask_proxy_usdt=393759, funding_indicative=0.000040, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=9048165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T21:45:01+00:00, last15m_closed_end=2026-11-07T21:45+00:00, prior8high=0.000005, depth_time=2026-11-07T21:45:17+00:00, book20_bid_proxy_usdt=37546, book20_ask_proxy_usdt=42909, funding_indicative=0.000036, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=45134051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T21:45:01+00:00, last15m_closed_end=2026-11-07T21:45+00:00, prior8high=199.010000, depth_time=2026-11-07T21:45:19+00:00, book20_bid_proxy_usdt=68489, book20_ask_proxy_usdt=40714, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=42949885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-07T21:45:01+00:00, last15m_closed_end=2026-11-07T21:45+00:00, prior8high=0.442100, depth_time=2026-11-07T21:45:15+00:00, book20_bid_proxy_usdt=351452, book20_ask_proxy_usdt=333300, funding_indicative=0.000027, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6745117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T21:45:01+00:00, last15m_closed_end=2026-11-07T21:45+00:00, prior8high=0.124500, depth_time=2026-11-07T21:45:07+00:00, book20_bid_proxy_usdt=246572, book20_ask_proxy_usdt=158605, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=11254516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T21:45:01+00:00, last15m_closed_end=2026-11-07T21:45+00:00, prior8high=0.334600, depth_time=2026-11-07T21:45:12+00:00, book20_bid_proxy_usdt=3885624, book20_ask_proxy_usdt=3358886, funding_indicative=-0.000171, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=26119297. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
