# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T17:15:34Z**
- feed_generated_utc: 2026-10-28T17:15:38+00:00
- source_sha256: `4914f27950ab820e95913eec91f574f763cd246d78563018fe354ca97f721a87`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T17:15+00:00, close=80477, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T17:00+00:00, close=80591.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.059890|-2.72|-26.01|-2.66|5315116|8.35|
|WLD_USDT|0.422900|-2.28|-26.27|-2.22|63584072|2.36|
|STRK_USDT|0.045750|-2.24|-26.17|-2.18|5190213|2.19|
|TIA_USDT|0.529200|-2.01|-16.33|-1.95|14350761|1.89|
|ARB_USDT|0.165220|-1.48|-15.96|-1.42|18205546|0.60|
|FET_USDT|0.179100|-1.43|-10.71|-1.37|5993583|5.58|
|ONDO_USDT|0.413400|-1.38|-11.40|-1.32|16836084|2.42|
|OP_USDT|0.109630|-1.30|-16.88|-1.24|6325374|2.74|
|APT_USDT|0.679800|-1.29|-18.64|-1.23|6148961|1.47|
|HBAR_USDT|0.074950|-1.26|-12.78|-1.20|10379566|1.33|
|NEAR_USDT|4.575000|-1.16|-15.04|-1.10|90466390|2.19|
|DOT_USDT|0.992300|-1.12|-15.89|-1.06|12204136|1.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.679800|0.677300|0.679800|0.31|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165220|0.164410|0.165220|0.29|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.059890|0.059390|0.059870|0.67|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.992300|0.987000|0.992300|1.26|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.179100|0.178500|0.179100|1.25|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074950|0.074680|0.074950|2.26|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.575000|4.557000|4.575000|0.99|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.413400|0.413000|0.413400|0.35|N|Y/Y|N/N|Y|N|
|OP_USDT|0.109630|0.109270|0.109650|0.74|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045750|0.045520|0.045750|1.31|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.529200|0.526600|0.529200|0.92|N|Y/N|N/Y|Y|N|
|WLD_USDT|0.422900|0.416900|0.422900|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.690600, depth_time=2026-10-28T17:15:24+00:00, book20_bid_proxy_usdt=204313, book20_ask_proxy_usdt=158313, funding_indicative=-0.000108, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=6148961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.167890, depth_time=2026-10-28T17:15:16+00:00, book20_bid_proxy_usdt=99945, book20_ask_proxy_usdt=81342, funding_indicative=-0.000031, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=18205546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.068880, depth_time=2026-10-28T17:15:04+00:00, book20_bid_proxy_usdt=29188, book20_ask_proxy_usdt=9978, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=5315116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=1.010500, depth_time=2026-10-28T17:15:33+00:00, book20_bid_proxy_usdt=392270, book20_ask_proxy_usdt=349934, funding_indicative=-0.000001, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=12204136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.182500, depth_time=2026-10-28T17:15:19+00:00, book20_bid_proxy_usdt=1599552, book20_ask_proxy_usdt=1097222, funding_indicative=0.000024, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=5993583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.075940, depth_time=2026-10-28T17:15:26+00:00, book20_bid_proxy_usdt=1673793, book20_ask_proxy_usdt=1489428, funding_indicative=-0.000012, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=10379566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=4.646000, depth_time=2026-10-28T17:15:31+00:00, book20_bid_proxy_usdt=4784065, book20_ask_proxy_usdt=6037995, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=90466390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.419600, depth_time=2026-10-28T17:15:20+00:00, book20_bid_proxy_usdt=1586932, book20_ask_proxy_usdt=1847114, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=16836084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.111260, depth_time=2026-10-28T17:15:23+00:00, book20_bid_proxy_usdt=162387, book20_ask_proxy_usdt=137943, funding_indicative=-0.000052, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=6325374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.047080, depth_time=2026-10-28T17:15:12+00:00, book20_bid_proxy_usdt=641394, book20_ask_proxy_usdt=829013, funding_indicative=0.000004, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=5190213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.546100, depth_time=2026-10-28T17:15:14+00:00, book20_bid_proxy_usdt=255283, book20_ask_proxy_usdt=362680, funding_indicative=0.000016, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=14350761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T17:15:00+00:00, last15m_closed_end=2026-10-28T17:15+00:00, prior8high=0.435200, depth_time=2026-10-28T17:15:10+00:00, book20_bid_proxy_usdt=3430108, book20_ask_proxy_usdt=4077841, funding_indicative=0.000012, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=63584072. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
