# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T09:00:19Z**
- feed_generated_utc: 2026-10-19T09:00:21+00:00
- source_sha256: `3f6e97781ffc03ac6e16e76cb0a4235d80b6e8a0dab2202de00d412e5a5b728d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T09:00+00:00, close=82786, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T09:00+00:00, close=82786, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.168600|-8.36|59.05|-10.39|6641283|5.93|
|BTW_USDT|2.222300|-3.60|32.10|-5.63|21201392|2.25|
|STRK_USDT|0.059370|-3.55|-50.22|-5.58|17802174|3.37|
|HBAR_USDT|0.084590|-3.10|-9.79|-5.13|46467416|1.18|
|SAND_USDT|0.058930|-2.15|-11.30|-4.18|16740090|3.39|
|TIA_USDT|0.607300|-1.71|3.15|-3.74|55161117|1.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.222300|2.206900|2.217800|0.97|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084590|0.084210|0.084590|0.67|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.168600|0.167000|0.168600|1.46|N|Y/Y|Y/N|N|N|
|SAND_USDT|0.058930|0.058430|0.058930|1.11|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059370|0.059240|0.059370|1.35|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.607300|0.606000|0.607400|0.58|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T09:00:02+00:00, last15m_closed_end=2026-10-19T09:00+00:00, prior8high=2.290900, depth_time=2026-10-19T09:00:09+00:00, book20_bid_proxy_usdt=11571, book20_ask_proxy_usdt=14705, funding_indicative=-0.000411, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.60%, turnover=21201392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T09:00:02+00:00, last15m_closed_end=2026-10-19T09:00+00:00, prior8high=0.085160, depth_time=2026-10-19T09:00:14+00:00, book20_bid_proxy_usdt=851461, book20_ask_proxy_usdt=469275, funding_indicative=-0.000065, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=46467416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T09:00:02+00:00, last15m_closed_end=2026-10-19T09:00+00:00, prior8high=0.175400, depth_time=2026-10-19T09:00:06+00:00, book20_bid_proxy_usdt=214003, book20_ask_proxy_usdt=120017, funding_indicative=-0.000255, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.36%, turnover=6641283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T09:00:02+00:00, last15m_closed_end=2026-10-19T09:00+00:00, prior8high=0.061170, depth_time=2026-10-19T09:00:16+00:00, book20_bid_proxy_usdt=507033, book20_ask_proxy_usdt=643772, funding_indicative=-0.005642, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=16740090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T09:00:02+00:00, last15m_closed_end=2026-10-19T09:00+00:00, prior8high=0.060350, depth_time=2026-10-19T09:00:10+00:00, book20_bid_proxy_usdt=788277, book20_ask_proxy_usdt=639260, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=17802174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T09:00:02+00:00, last15m_closed_end=2026-10-19T09:00+00:00, prior8high=0.620500, depth_time=2026-10-19T09:00:18+00:00, book20_bid_proxy_usdt=342507, book20_ask_proxy_usdt=211315, funding_indicative=-0.000034, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=55161117. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
