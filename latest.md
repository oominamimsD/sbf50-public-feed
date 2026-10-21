# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T16:30:17Z**
- feed_generated_utc: 2026-10-21T16:30:20+00:00
- source_sha256: `a39a0b1bc79ff79cb28e51886828bede9a6894da5fce8025ffb47adc66349d9f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T16:30+00:00, close=84682.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002366|-16.80|66.85|-17.02|9075519|8.45|
|BR_USDT|0.527740|-2.55|29.42|-2.77|17350004|3.41|
|AKE_USDT|0.026408|-1.05|2.03|-1.27|9874725|3.41|
|ICNT_USDT|0.187000|-0.79|70.93|-1.01|5742979|5.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026408|0.026202|0.026402|0.65|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.527740|0.523700|0.528310|0.86|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002366|0.002323|0.002376|1.19|N|Y/N|N/N|N|N|
|ICNT_USDT|0.187000|0.185500|0.187000|0.50|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T16:30:02+00:00, last15m_closed_end=2026-10-21T16:30+00:00, prior8high=0.027884, depth_time=2026-10-21T16:30:13+00:00, book20_bid_proxy_usdt=10366, book20_ask_proxy_usdt=10670, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=9874725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T16:30:02+00:00, last15m_closed_end=2026-10-21T16:30+00:00, prior8high=0.591780, depth_time=2026-10-21T16:30:11+00:00, book20_bid_proxy_usdt=2494, book20_ask_proxy_usdt=2598, funding_indicative=-0.000093, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=17350004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T16:30:02+00:00, last15m_closed_end=2026-10-21T16:30+00:00, prior8high=0.004584, depth_time=2026-10-21T16:30:09+00:00, book20_bid_proxy_usdt=178579, book20_ask_proxy_usdt=73367, funding_indicative=-0.007131, next_funding_utc=2026-10-21T17:00:00+00:00, funding_cycle_h=1, 24h_change=-16.80%, turnover=9075519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-21T16:30:02+00:00, last15m_closed_end=2026-10-21T16:30+00:00, prior8high=0.196000, depth_time=2026-10-21T16:30:15+00:00, book20_bid_proxy_usdt=186141, book20_ask_proxy_usdt=134534, funding_indicative=-0.000118, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=5742979. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
