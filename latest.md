# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T20:45:11Z**
- feed_generated_utc: 2026-11-09T20:45:12+00:00
- source_sha256: `139acdcb91af9824968e01d932df8a96b328f0c48a40dc8215314b86222f3146`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T20:45+00:00, close=74748.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1168.130000|-4.69|-6.85|-3.71|2552841682|0.09|
|QNT_USDT|195.810000|-2.11|-3.27|-1.13|44571670|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.810000|195.310000|195.890000|2.48|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1168.130000|1161.730000|1167.340000|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-09T20:45:03+00:00, last15m_closed_end=2026-11-09T20:45+00:00, prior8high=197.570000, depth_time=2026-11-09T20:45:09+00:00, book20_bid_proxy_usdt=84245, book20_ask_proxy_usdt=40596, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=44571670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T20:45:03+00:00, last15m_closed_end=2026-11-09T20:45+00:00, prior8high=1189.910000, depth_time=2026-11-09T20:45:06+00:00, book20_bid_proxy_usdt=992251, book20_ask_proxy_usdt=71957, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.69%, turnover=2552841682. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
