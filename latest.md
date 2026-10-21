# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T20:00:21Z**
- feed_generated_utc: 2026-10-21T20:00:24+00:00
- source_sha256: `9cffb6094adaafc638ad1ad30fde7457f383694f30e3b9b6e2d6eb45b7cafe4f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002475|-40.10|74.54|-40.04|9042782|4.04|
|BR_USDT|0.495390|-14.46|21.49|-14.40|14370759|0.81|
|AKE_USDT|0.025543|-4.29|-1.30|-4.23|10147168|3.13|
|INJ_USDT|8.519000|-2.64|11.51|-2.58|56294269|1.18|
|WLD_USDT|0.569400|-1.47|16.46|-1.41|133491684|1.76|
|JCT_USDT|0.004190|-1.34|99.42|-1.28|14751085|9.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025543|0.025328|0.025529|0.82|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.495390|0.495130|0.495420|0.79|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002475|0.002138|0.002474|0.25|N|Y/Y|N/N|N|N|
|INJ_USDT|8.519000|8.474000|8.519000|0.37|N|Y/Y|Y/N|N|N|
|JCT_USDT|0.004190|0.004130|0.004193|0.50|N|Y/Y|N/N|N|N|
|WLD_USDT|0.569400|0.565600|0.569400|0.38|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T20:00:01+00:00, last15m_closed_end=2026-10-21T20:00+00:00, prior8high=0.026400, depth_time=2026-10-21T20:00:11+00:00, book20_bid_proxy_usdt=16077, book20_ask_proxy_usdt=14326, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=10147168. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T20:00:01+00:00, last15m_closed_end=2026-10-21T20:00+00:00, prior8high=0.528660, depth_time=2026-10-21T20:00:11+00:00, book20_bid_proxy_usdt=13844, book20_ask_proxy_usdt=3540, funding_indicative=-0.000107, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.46%, turnover=14370759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T20:00:01+00:00, last15m_closed_end=2026-10-21T20:00+00:00, prior8high=0.002473, depth_time=2026-10-21T20:00:08+00:00, book20_bid_proxy_usdt=97831, book20_ask_proxy_usdt=164244, funding_indicative=0.000012, next_funding_utc=2026-10-21T21:00:00+00:00, funding_cycle_h=1, 24h_change=-40.10%, turnover=9042782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T20:00:01+00:00, last15m_closed_end=2026-10-21T20:00+00:00, prior8high=8.717000, depth_time=2026-10-21T20:00:15+00:00, book20_bid_proxy_usdt=105869, book20_ask_proxy_usdt=177139, funding_indicative=0.000055, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=56294269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T20:00:01+00:00, last15m_closed_end=2026-10-21T20:00+00:00, prior8high=0.004433, depth_time=2026-10-21T20:00:20+00:00, book20_bid_proxy_usdt=51503, book20_ask_proxy_usdt=27394, funding_indicative=0.000122, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=14751085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-21T20:00:01+00:00, last15m_closed_end=2026-10-21T20:00+00:00, prior8high=0.577500, depth_time=2026-10-21T20:00:18+00:00, book20_bid_proxy_usdt=1718896, book20_ask_proxy_usdt=1733203, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=133491684. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
