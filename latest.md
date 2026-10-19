# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T02:45:23Z**
- feed_generated_utc: 2026-10-19T02:45:24+00:00
- source_sha256: `cca69ca6faa7d647faaf43587356bf632d8333bd5db730d4959feb08854511cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T02:45+00:00, close=82532.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T02:00+00:00, close=82415, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.111775|-8.36|294.65|-10.08|9484102|2.23|
|AGT_USDT|0.062800|-7.00|255.10|-8.72|9055668|4.94|
|BAT_USDT|0.171070|-2.45|2.65|-4.17|6424298|0.58|
|BTW_USDT|2.252100|-2.31|33.87|-4.03|22291979|2.22|
|ICNT_USDT|0.175800|-2.00|65.84|-3.72|7734589|5.69|
|HBAR_USDT|0.084280|-1.74|-10.13|-3.46|51623710|1.19|
|STRK_USDT|0.060860|-1.13|-48.97|-2.85|17276740|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062800|0.061150|0.063008|0.51|N|Y/Y|N/N|N|N|
|BAT_USDT|0.171070|0.171140|0.171050|1.11|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.252100|2.230700|2.252100|0.65|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084280|0.083740|0.084280|0.46|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.175800|0.175900|0.175800|3.24|Y|Y/Y|N/N|N|N|
|Q_USDT|0.111775|0.106082|0.112143|0.33|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060860|0.059820|0.060860|0.38|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T02:45:01+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=0.066300, depth_time=2026-10-19T02:45:09+00:00, book20_bid_proxy_usdt=1695, book20_ask_proxy_usdt=3074, funding_indicative=0.000124, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.00%, turnover=9055668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-19T02:45:02+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=0.176080, depth_time=2026-10-19T02:45:11+00:00, book20_bid_proxy_usdt=21090, book20_ask_proxy_usdt=23598, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=6424298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T02:45:01+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=2.355100, depth_time=2026-10-19T02:45:14+00:00, book20_bid_proxy_usdt=8564, book20_ask_proxy_usdt=14442, funding_indicative=-0.000326, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=22291979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T02:45:01+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=0.084860, depth_time=2026-10-19T02:45:19+00:00, book20_bid_proxy_usdt=842677, book20_ask_proxy_usdt=963920, funding_indicative=-0.000016, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=51623710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T02:45:01+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=0.183900, depth_time=2026-10-19T02:45:13+00:00, book20_bid_proxy_usdt=164895, book20_ask_proxy_usdt=123354, funding_indicative=-0.000009, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=7734589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T02:45:01+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=0.118711, depth_time=2026-10-19T02:45:07+00:00, book20_bid_proxy_usdt=6452, book20_ask_proxy_usdt=7567, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.36%, turnover=9484102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T02:45:02+00:00, last15m_closed_end=2026-10-19T02:45+00:00, prior8high=0.061960, depth_time=2026-10-19T02:45:22+00:00, book20_bid_proxy_usdt=455930, book20_ask_proxy_usdt=251159, funding_indicative=0.000009, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=17276740. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
