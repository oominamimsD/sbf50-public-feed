# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T11:30:26Z**
- feed_generated_utc: 2026-10-28T11:30:33+00:00
- source_sha256: `90ec6b34def14f260c873d962ed2b92556a96e5a5ac0534d126b53983314900c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.12 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T11:30+00:00, close=81359.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T11:00+00:00, close=81460.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055160|-13.24|-55.06|-14.26|20655816|5.44|
|BEAT_USDT|0.079600|-12.61|6.54|-13.63|16053766|1.25|
|AKE_USDT|0.019795|-6.29|-36.33|-7.31|6419080|0.51|
|ENA_USDT|0.203450|-4.38|7.14|-5.40|72355612|6.39|
|INJ_USDT|7.919000|-3.33|-7.91|-4.35|24576023|1.26|
|DASH_USDT|53.590000|-1.07|7.30|-2.09|16137219|1.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019795|0.019671|0.019833|0.68|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.079600|0.083760|0.079730|3.71|Y|Y/Y|N/N|N|N|
|DASH_USDT|53.590000|53.510000|53.600000|1.46|N|Y/Y|N/N|N|N|
|ENA_USDT|0.203450|0.203360|0.203590|3.65|N|Y/Y|N/N|N|N|
|INJ_USDT|7.919000|7.897000|7.920000|0.43|N|Y/Y|N/N|N|N|
|Q_USDT|0.055160|0.055230|0.055300|1.30|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T11:30:08+00:00, last15m_closed_end=2026-10-28T11:30+00:00, prior8high=0.021104, depth_time=2026-10-28T11:30:17+00:00, book20_bid_proxy_usdt=8636, book20_ask_proxy_usdt=5085, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.29%, turnover=6419080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T11:30:08+00:00, last15m_closed_end=2026-10-28T11:30+00:00, prior8high=0.096300, depth_time=2026-10-28T11:30:15+00:00, book20_bid_proxy_usdt=4300, book20_ask_proxy_usdt=12905, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.61%, turnover=16053766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T11:30:08+00:00, last15m_closed_end=2026-10-28T11:30+00:00, prior8high=54.240000, depth_time=2026-10-28T11:30:24+00:00, book20_bid_proxy_usdt=870542, book20_ask_proxy_usdt=897895, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=16137219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T11:30:08+00:00, last15m_closed_end=2026-10-28T11:30+00:00, prior8high=0.208060, depth_time=2026-10-28T11:30:20+00:00, book20_bid_proxy_usdt=178416, book20_ask_proxy_usdt=154537, funding_indicative=0.000041, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=72355612. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T11:30:08+00:00, last15m_closed_end=2026-10-28T11:30+00:00, prior8high=7.998000, depth_time=2026-10-28T11:30:23+00:00, book20_bid_proxy_usdt=311688, book20_ask_proxy_usdt=291320, funding_indicative=0.000234, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=24576023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T11:30:07+00:00, last15m_closed_end=2026-10-28T11:30+00:00, prior8high=0.059890, depth_time=2026-10-28T11:30:13+00:00, book20_bid_proxy_usdt=32113, book20_ask_proxy_usdt=30583, funding_indicative=-0.000325, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.24%, turnover=20655816. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
