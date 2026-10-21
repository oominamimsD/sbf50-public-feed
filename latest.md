# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T18:00:16Z**
- feed_generated_utc: 2026-10-21T18:00:18+00:00
- source_sha256: `49646ccfb4fcfd9270e3e4f3402531f5ed83ed7494bfdf7a2f1b1b267dfc062f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T18:00+00:00, close=84635.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T18:00+00:00, close=84635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002243|-21.13|58.18|-21.29|9340940|4.46|
|BR_USDT|0.518500|-4.25|27.16|-4.41|16165785|1.54|
|AKE_USDT|0.026144|-2.04|1.01|-2.20|10061542|0.38|
|INJ_USDT|8.612000|-1.66|12.73|-1.82|56788789|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026144|0.025666|0.026144|0.26|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.518500|0.513880|0.518530|0.45|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002243|0.002080|0.002243|0.30|N|Y/Y|N/N|N|N|
|INJ_USDT|8.612000|8.565000|8.612000|1.65|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T17:59:59+00:00, last15m_closed_end=2026-10-21T18:00+00:00, prior8high=0.027169, depth_time=2026-10-21T18:00:13+00:00, book20_bid_proxy_usdt=12178, book20_ask_proxy_usdt=13159, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=10061542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T17:59:59+00:00, last15m_closed_end=2026-10-21T18:00+00:00, prior8high=0.546740, depth_time=2026-10-21T18:00:10+00:00, book20_bid_proxy_usdt=3627, book20_ask_proxy_usdt=2172, funding_indicative=-0.000124, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=16165785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T17:59:59+00:00, last15m_closed_end=2026-10-21T18:00+00:00, prior8high=0.003221, depth_time=2026-10-21T18:00:08+00:00, book20_bid_proxy_usdt=135904, book20_ask_proxy_usdt=169682, funding_indicative=-0.000390, next_funding_utc=2026-10-21T19:00:00+00:00, funding_cycle_h=1, 24h_change=-21.13%, turnover=9340940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T17:59:59+00:00, last15m_closed_end=2026-10-21T18:00+00:00, prior8high=8.793000, depth_time=2026-10-21T18:00:15+00:00, book20_bid_proxy_usdt=220571, book20_ask_proxy_usdt=243416, funding_indicative=0.000038, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=56788789. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
