# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T20:15:18Z**
- feed_generated_utc: 2026-10-21T20:15:20+00:00
- source_sha256: `4a0bda5af7beafb66ff2939ba4a1f154ee4294694060efc1ff88f13b85e6a42c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T20:15+00:00, close=84479.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002491|-12.41|75.66|-12.39|9075686|8.04|
|BR_USDT|0.489560|-9.60|20.06|-9.58|14561170|1.02|
|AKE_USDT|0.025710|-3.67|-0.66|-3.65|10216203|1.94|
|INJ_USDT|8.524000|-2.67|11.58|-2.65|56551422|1.17|
|TIA_USDT|0.619600|-2.03|16.13|-2.01|39449608|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025710|0.025195|0.025710|1.15|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.489560|0.492440|0.489680|1.52|Y|Y/Y|Y/Y|N|Y|
|DOOD_USDT|0.002491|0.002197|0.002491|0.56|N|Y/Y|N/N|N|N|
|INJ_USDT|8.524000|8.474000|8.524000|0.65|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.619600|0.614400|0.619600|0.86|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T20:15:00+00:00, last15m_closed_end=2026-10-21T20:15+00:00, prior8high=0.026144, depth_time=2026-10-21T20:15:12+00:00, book20_bid_proxy_usdt=10812, book20_ask_proxy_usdt=14694, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.67%, turnover=10216203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T20:15:00+00:00, last15m_closed_end=2026-10-21T20:15+00:00, prior8high=0.528660, depth_time=2026-10-21T20:15:10+00:00, book20_bid_proxy_usdt=3455, book20_ask_proxy_usdt=5250, funding_indicative=-0.000102, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.60%, turnover=14561170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T20:15:00+00:00, last15m_closed_end=2026-10-21T20:15+00:00, prior8high=0.002486, depth_time=2026-10-21T20:15:07+00:00, book20_bid_proxy_usdt=139985, book20_ask_proxy_usdt=84145, funding_indicative=0.000012, next_funding_utc=2026-10-21T21:00:00+00:00, funding_cycle_h=1, 24h_change=-12.41%, turnover=9075686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T20:15:00+00:00, last15m_closed_end=2026-10-21T20:15+00:00, prior8high=8.717000, depth_time=2026-10-21T20:15:14+00:00, book20_bid_proxy_usdt=209664, book20_ask_proxy_usdt=300059, funding_indicative=0.000099, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=56551422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T20:15:00+00:00, last15m_closed_end=2026-10-21T20:15+00:00, prior8high=0.635600, depth_time=2026-10-21T20:15:16+00:00, book20_bid_proxy_usdt=189524, book20_ask_proxy_usdt=307621, funding_indicative=-0.000070, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=39449608. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
