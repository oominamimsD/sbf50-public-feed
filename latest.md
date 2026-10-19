# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T06:30:18Z**
- feed_generated_utc: 2026-10-19T06:30:19+00:00
- source_sha256: `81fa8ef490bb8d1f93448920e5e4fe3ea92720a8c8c86deff981e2d741ba554b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T06:30+00:00, close=82702.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T06:00+00:00, close=82726.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.170400|-5.01|60.75|-6.95|7207351|5.87|
|STRK_USDT|0.059660|-3.08|-49.97|-5.02|17527150|1.68|
|HBAR_USDT|0.084120|-1.93|-10.30|-3.87|50808117|1.19|
|TIA_USDT|0.609800|-1.31|3.58|-3.25|57902576|3.28|
|BTW_USDT|2.292400|-0.56|36.27|-2.50|21708405|0.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.292400|2.166400|2.292300|1.41|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084120|0.083810|0.084110|1.33|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.170400|0.168800|0.170400|0.61|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059660|0.059440|0.059650|1.78|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.609800|0.604400|0.609800|1.02|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T06:30:01+00:00, last15m_closed_end=2026-10-19T06:30+00:00, prior8high=2.328900, depth_time=2026-10-19T06:30:17+00:00, book20_bid_proxy_usdt=11704, book20_ask_proxy_usdt=16312, funding_indicative=-0.000131, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.56%, turnover=21708405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T06:30:01+00:00, last15m_closed_end=2026-10-19T06:30+00:00, prior8high=0.084640, depth_time=2026-10-19T06:30:12+00:00, book20_bid_proxy_usdt=611593, book20_ask_proxy_usdt=1199982, funding_indicative=-0.000033, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=50808117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T06:30:01+00:00, last15m_closed_end=2026-10-19T06:30+00:00, prior8high=0.194500, depth_time=2026-10-19T06:30:07+00:00, book20_bid_proxy_usdt=150008, book20_ask_proxy_usdt=104917, funding_indicative=-0.000181, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.01%, turnover=7207351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T06:30:01+00:00, last15m_closed_end=2026-10-19T06:30+00:00, prior8high=0.060780, depth_time=2026-10-19T06:30:09+00:00, book20_bid_proxy_usdt=887935, book20_ask_proxy_usdt=540193, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=17527150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T06:30:01+00:00, last15m_closed_end=2026-10-19T06:30+00:00, prior8high=0.616500, depth_time=2026-10-19T06:30:14+00:00, book20_bid_proxy_usdt=145876, book20_ask_proxy_usdt=264047, funding_indicative=-0.000020, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=57902576. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
