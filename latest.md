# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T01:15:20Z**
- feed_generated_utc: 2026-10-21T01:15:23+00:00
- source_sha256: `077b32ab4c4d2cc8584ba0f9adea6495e578a5242a9c9d6d13a145cbf0f51d52`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T01:15+00:00, close=82792.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T01:00+00:00, close=82991, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.190280|-11.81|7.27|-12.06|10199761|0.53|
|XMR_USDT|582.940000|-6.00|10.42|-6.25|17045907|0.17|
|AGT_USDT|0.063341|-1.99|291.54|-2.24|7235140|3.15|
|TIA_USDT|0.610500|-1.95|5.75|-2.20|47695625|1.64|
|PHA_USDT|0.057260|-0.96|4.05|-1.21|9797952|3.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063341|0.055541|0.063341|2.05|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.190280|0.191090|0.190280|1.24|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057260|0.057180|0.057260|2.07|N|Y/Y|N/N|N|N|
|TIA_USDT|0.610500|0.607500|0.610500|1.85|N|Y/Y|Y/Y|N|N|
|XMR_USDT|582.940000|582.440000|582.940000|3.01|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T01:15:00+00:00, last15m_closed_end=2026-10-21T01:15+00:00, prior8high=0.069341, depth_time=2026-10-21T01:15:14+00:00, book20_bid_proxy_usdt=8248, book20_ask_proxy_usdt=11671, funding_indicative=0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=7235140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T01:15:00+00:00, last15m_closed_end=2026-10-21T01:15+00:00, prior8high=0.195840, depth_time=2026-10-21T01:15:08+00:00, book20_bid_proxy_usdt=20762, book20_ask_proxy_usdt=27310, funding_indicative=0.000072, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.81%, turnover=10199761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T01:15:00+00:00, last15m_closed_end=2026-10-21T01:15+00:00, prior8high=0.058570, depth_time=2026-10-21T01:15:18+00:00, book20_bid_proxy_usdt=72011, book20_ask_proxy_usdt=75489, funding_indicative=-0.000062, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=9797952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T01:15:00+00:00, last15m_closed_end=2026-10-21T01:15+00:00, prior8high=0.625200, depth_time=2026-10-21T01:15:17+00:00, book20_bid_proxy_usdt=159641, book20_ask_proxy_usdt=273296, funding_indicative=-0.000057, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=47695625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T01:15:00+00:00, last15m_closed_end=2026-10-21T01:15+00:00, prior8high=613.100000, depth_time=2026-10-21T01:15:12+00:00, book20_bid_proxy_usdt=14746, book20_ask_proxy_usdt=20743, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.00%, turnover=17045907. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
