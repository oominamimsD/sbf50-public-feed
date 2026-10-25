# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T03:45:21Z**
- feed_generated_utc: 2026-10-25T03:45:24+00:00
- source_sha256: `85eb608b7ea7bbaee3e1c64854932a16f21df2993cfc921737709b28ab50ceaf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T03:45+00:00, close=80890.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T03:00+00:00, close=80875.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.054550|-19.06|76.25|-20.47|13516894|1.83|
|BIRB_USDT|0.079910|-18.17|64.69|-19.58|9282598|3.77|
|BTW_USDT|1.700300|-2.35|-25.07|-3.76|10116076|2.35|
|STRK_USDT|0.046800|0.14|-29.25|-1.27|8498804|2.14|
|DOT_USDT|1.041400|0.22|-6.80|-1.19|11621535|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.079910|0.069430|0.079910|1.26|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.700300|1.714500|1.700300|0.98|N|N/N|Y/Y|Y|N|
|DOT_USDT|1.041400|1.040400|1.041500|1.05|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.054550|0.050530|0.054550|0.84|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046800|0.046250|0.046800|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T03:45:01+00:00, last15m_closed_end=2026-10-25T03:45+00:00, prior8high=0.088490, depth_time=2026-10-25T03:45:12+00:00, book20_bid_proxy_usdt=10836, book20_ask_proxy_usdt=18331, funding_indicative=-0.009499, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.17%, turnover=9282598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T03:45:01+00:00, last15m_closed_end=2026-10-25T03:45+00:00, prior8high=1.754800, depth_time=2026-10-25T03:45:15+00:00, book20_bid_proxy_usdt=9503, book20_ask_proxy_usdt=15292, funding_indicative=-0.003701, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=10116076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T03:45:01+00:00, last15m_closed_end=2026-10-25T03:45+00:00, prior8high=1.055300, depth_time=2026-10-25T03:45:20+00:00, book20_bid_proxy_usdt=299062, book20_ask_proxy_usdt=547531, funding_indicative=-0.000117, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.22%, turnover=11621535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T03:45:01+00:00, last15m_closed_end=2026-10-25T03:45+00:00, prior8high=0.058640, depth_time=2026-10-25T03:45:10+00:00, book20_bid_proxy_usdt=49396, book20_ask_proxy_usdt=72734, funding_indicative=-0.001147, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-19.06%, turnover=13516894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T03:45:01+00:00, last15m_closed_end=2026-10-25T03:45+00:00, prior8high=0.047120, depth_time=2026-10-25T03:45:17+00:00, book20_bid_proxy_usdt=822455, book20_ask_proxy_usdt=684859, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.14%, turnover=8498804. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
