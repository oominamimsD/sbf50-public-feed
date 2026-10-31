# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T13:15:37Z**
- feed_generated_utc: 2026-10-31T13:15:39+00:00
- source_sha256: `9a8efc3eb2e4bf1e35f5f47db935f52c5d4811f27f49a21debe7255289c2529f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T13:15+00:00, close=77452, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T13:00+00:00, close=77509.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011878|-37.22|-66.05|-37.06|11443328|1.68|
|Q_USDT|0.031880|-32.85|-73.05|-32.69|12145646|3.13|
|BTW_USDT|1.111400|-7.34|-34.71|-7.18|8415672|3.61|
|BEAT_USDT|0.099270|-5.59|36.75|-5.43|7273784|2.02|
|HYPE_USDT|87.264000|-5.50|11.30|-5.34|94452539|0.12|
|TRX_USDT|0.317680|-5.31|-3.54|-5.15|6659174|0.63|
|IDOL_USDT|0.019232|-4.98|142.82|-4.82|15955572|1.56|
|WLD_USDT|0.396700|-3.69|-25.48|-3.53|42744027|2.52|
|FET_USDT|0.161000|-3.36|-14.04|-3.20|6087633|6.21|
|DASH_USDT|47.780000|-2.56|-11.27|-2.40|9562500|2.09|
|DOT_USDT|0.953400|-1.63|-15.38|-1.47|8612212|1.05|
|LTC_USDT|55.020000|-1.25|-5.86|-1.09|5774927|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011878|0.010909|0.011883|0.73|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099270|0.099280|0.099260|0.59|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.111400|1.081300|1.111400|0.99|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.780000|47.700000|47.770000|4.93|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.953400|0.953200|0.953700|15.74|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161000|0.160400|0.160900|2.10|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.264000|87.134000|87.229000|3.55|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019232|0.018656|0.019232|0.64|N|Y/Y|N/N|Y|N|
|LTC_USDT|55.020000|54.780000|55.020000|0.82|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031880|0.031390|0.031880|0.46|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.317680|0.317290|0.317610|0.19|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396700|0.394200|0.396300|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.012080, depth_time=2026-10-31T13:15:08+00:00, book20_bid_proxy_usdt=11053, book20_ask_proxy_usdt=10363, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.22%, turnover=11443328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.103100, depth_time=2026-10-31T13:15:15+00:00, book20_bid_proxy_usdt=14229, book20_ask_proxy_usdt=11257, funding_indicative=0.000186, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.59%, turnover=7273784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=1.204600, depth_time=2026-10-31T13:15:14+00:00, book20_bid_proxy_usdt=15384, book20_ask_proxy_usdt=12527, funding_indicative=-0.000386, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.34%, turnover=8415672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=48.200000, depth_time=2026-10-31T13:15:29+00:00, book20_bid_proxy_usdt=743749, book20_ask_proxy_usdt=719099, funding_indicative=-0.000116, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=9562500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.958600, depth_time=2026-10-31T13:15:34+00:00, book20_bid_proxy_usdt=372229, book20_ask_proxy_usdt=521297, funding_indicative=0.000013, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=8612212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.161800, depth_time=2026-10-31T13:15:26+00:00, book20_bid_proxy_usdt=1139739, book20_ask_proxy_usdt=869568, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=6087633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=88.782000, depth_time=2026-10-31T13:15:19+00:00, book20_bid_proxy_usdt=106957, book20_ask_proxy_usdt=109658, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.50%, turnover=94452539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.019922, depth_time=2026-10-31T13:15:24+00:00, book20_bid_proxy_usdt=5506, book20_ask_proxy_usdt=4642, funding_indicative=0.000301, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.98%, turnover=15955572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=55.120000, depth_time=2026-10-31T13:15:34+00:00, book20_bid_proxy_usdt=1418310, book20_ask_proxy_usdt=1832063, funding_indicative=-0.000061, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=5774927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.033230, depth_time=2026-10-31T13:15:11+00:00, book20_bid_proxy_usdt=49718, book20_ask_proxy_usdt=38606, funding_indicative=-0.000465, next_funding_utc=2026-10-31T14:00:00+00:00, funding_cycle_h=1, 24h_change=-32.85%, turnover=12145646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.322470, depth_time=2026-10-31T13:15:21+00:00, book20_bid_proxy_usdt=92290, book20_ask_proxy_usdt=89356, funding_indicative=-0.000919, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.31%, turnover=6659174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T13:15:04+00:00, last15m_closed_end=2026-10-31T13:15+00:00, prior8high=0.398800, depth_time=2026-10-31T13:15:24+00:00, book20_bid_proxy_usdt=3171063, book20_ask_proxy_usdt=3487484, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=42744027. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
