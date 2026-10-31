# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T08:30:34Z**
- feed_generated_utc: 2026-10-31T08:30:37+00:00
- source_sha256: `db9aeafc7ed607800681e136eff33c1635a919251b4f4b7d9a3dda701d2bb709`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T08:30+00:00, close=77337.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011083|-41.42|-68.33|-41.11|9637970|6.32|
|Q_USDT|0.032370|-31.82|-72.64|-31.51|18078687|3.09|
|BEAT_USDT|0.096710|-8.02|33.22|-7.71|8202608|6.20|
|HYPE_USDT|87.211000|-5.55|11.23|-5.24|103834382|0.12|
|EVAA_USDT|1.219400|-4.89|132.31|-4.58|5615478|4.10|
|TRX_USDT|0.321050|-4.30|-2.51|-3.99|5797972|0.31|
|BTW_USDT|1.150300|-4.10|-32.43|-3.79|9503004|0.87|
|WLD_USDT|0.395900|-3.88|-25.63|-3.57|48584725|2.53|
|FET_USDT|0.161600|-3.00|-13.72|-2.69|6049799|6.19|
|DASH_USDT|47.700000|-2.73|-11.42|-2.42|13505490|2.10|
|LTC_USDT|54.620000|-1.97|-6.55|-1.66|6550272|3.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011083|0.009146|0.011052|4.99|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.096710|0.096500|0.096690|0.97|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.150300|1.124600|1.149900|0.67|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.700000|47.750000|47.700000|0.61|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.219400|1.168700|1.219400|0.30|N|N/N|N/N|Y|N|
|FET_USDT|0.161600|0.161900|0.161800|0.26|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.211000|87.501000|87.211000|2.24|Y|Y/Y|N/N|Y|N|
|LTC_USDT|54.620000|54.610000|54.620000|0.88|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.032370|0.031210|0.032440|0.50|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.321050|0.321100|0.321050|0.17|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395900|0.396300|0.395800|1.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=0.013245, depth_time=2026-10-31T08:30:09+00:00, book20_bid_proxy_usdt=16439, book20_ask_proxy_usdt=8843, funding_indicative=-0.001552, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-41.42%, turnover=9637970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=0.098520, depth_time=2026-10-31T08:30:12+00:00, book20_bid_proxy_usdt=19136, book20_ask_proxy_usdt=13646, funding_indicative=0.000168, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.02%, turnover=8202608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=1.181700, depth_time=2026-10-31T08:30:24+00:00, book20_bid_proxy_usdt=12611, book20_ask_proxy_usdt=13207, funding_indicative=-0.000339, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=9503004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=48.110000, depth_time=2026-10-31T08:30:27+00:00, book20_bid_proxy_usdt=1076004, book20_ask_proxy_usdt=766266, funding_indicative=0.000059, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=13505490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=1.226600, depth_time=2026-10-31T08:30:19+00:00, book20_bid_proxy_usdt=7249, book20_ask_proxy_usdt=5912, funding_indicative=0.000224, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=5615478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=0.164200, depth_time=2026-10-31T08:30:26+00:00, book20_bid_proxy_usdt=1311482, book20_ask_proxy_usdt=835250, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=6049799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=88.891000, depth_time=2026-10-31T08:30:16+00:00, book20_bid_proxy_usdt=193896, book20_ask_proxy_usdt=161636, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.55%, turnover=103834382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=55.350000, depth_time=2026-10-31T08:30:32+00:00, book20_bid_proxy_usdt=1245960, book20_ask_proxy_usdt=1016869, funding_indicative=0.000021, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=6550272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=0.033340, depth_time=2026-10-31T08:30:11+00:00, book20_bid_proxy_usdt=36846, book20_ask_proxy_usdt=44862, funding_indicative=-0.000742, next_funding_utc=2026-10-31T09:00:00+00:00, funding_cycle_h=1, 24h_change=-31.82%, turnover=18078687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=0.326220, depth_time=2026-10-31T08:30:21+00:00, book20_bid_proxy_usdt=246606, book20_ask_proxy_usdt=156086, funding_indicative=-0.000353, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=5797972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T08:30:02+00:00, last15m_closed_end=2026-10-31T08:30+00:00, prior8high=0.401700, depth_time=2026-10-31T08:30:24+00:00, book20_bid_proxy_usdt=3707694, book20_ask_proxy_usdt=2434998, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=48584725. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
