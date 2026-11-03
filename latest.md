# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T14:15:41Z**
- feed_generated_utc: 2026-11-03T14:15:43+00:00
- source_sha256: `638276cbd4c6b9de302a7dad807a62c6ead1646ae7299dc7abf990863a92f510`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T14:15+00:00, close=77229.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T14:00+00:00, close=77368.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004176|-24.10|-86.43|-23.75|12376251|2.40|
|BTW_USDT|0.988600|-9.86|-17.32|-9.51|8524394|4.06|
|XPL_USDT|0.064530|-7.25|-13.13|-6.90|11476551|3.10|
|UAI_USDT|0.125100|-5.72|-49.71|-5.37|8530153|7.99|
|TIA_USDT|0.440900|-3.50|-17.69|-3.15|13468776|2.27|
|NEAR_USDT|3.880000|-3.24|-15.15|-2.89|81916516|2.58|
|ENA_USDT|0.170240|-2.74|-19.07|-2.39|70679703|0.59|
|TRUMPOFFICIAL_USDT|1.592000|-2.68|-5.74|-2.33|7944947|6.28|
|WLD_USDT|0.371000|-2.67|-16.62|-2.32|48938913|2.70|
|DASH_USDT|46.040000|-2.45|-11.83|-2.10|9160361|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004176|0.004150|0.004176|3.59|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.988600|0.937700|0.988600|0.37|N|N/N|Y/Y|Y|N|
|DASH_USDT|46.040000|45.720000|46.060000|0.43|N|N/N|Y/Y|Y|N|
|ENA_USDT|0.170240|0.170200|0.170290|1.42|N|Y/N|Y/Y|Y|N|
|NEAR_USDT|3.880000|3.854000|3.880000|1.18|N|N/N|Y/Y|Y|N|
|TIA_USDT|0.440900|0.440700|0.441000|0.70|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.592000|1.583000|1.593000|1.17|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.125100|0.139600|0.125200|6.99|Y|Y/N|Y/Y|Y|N|
|WLD_USDT|0.371000|0.371000|0.371000|1.22|N|Y/N|Y/Y|Y|N|
|XPL_USDT|0.064530|0.064160|0.064560|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T14:15:03+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=0.004535, depth_time=2026-11-03T14:15:09+00:00, book20_bid_proxy_usdt=46327, book20_ask_proxy_usdt=50637, funding_indicative=-0.001059, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.10%, turnover=12376251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T14:15:04+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=1.032400, depth_time=2026-11-03T14:15:13+00:00, book20_bid_proxy_usdt=17412, book20_ask_proxy_usdt=14492, funding_indicative=0.000047, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=8524394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T14:15:04+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=46.820000, depth_time=2026-11-03T14:15:37+00:00, book20_bid_proxy_usdt=909598, book20_ask_proxy_usdt=586674, funding_indicative=0.000082, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=9160361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T14:15:03+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=0.174220, depth_time=2026-11-03T14:15:31+00:00, book20_bid_proxy_usdt=175953, book20_ask_proxy_usdt=154727, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=70679703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T14:15:03+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=3.945000, depth_time=2026-11-03T14:15:28+00:00, book20_bid_proxy_usdt=5941750, book20_ask_proxy_usdt=1738441, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=81916516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T14:15:04+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=0.449000, depth_time=2026-11-03T14:15:23+00:00, book20_bid_proxy_usdt=323999, book20_ask_proxy_usdt=324198, funding_indicative=-0.000006, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=13468776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T14:15:04+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=1.616000, depth_time=2026-11-03T14:15:34+00:00, book20_bid_proxy_usdt=2308224, book20_ask_proxy_usdt=2721095, funding_indicative=0.000030, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=7944947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-03T14:15:03+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=0.172500, depth_time=2026-11-03T14:15:21+00:00, book20_bid_proxy_usdt=115058, book20_ask_proxy_usdt=110662, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.72%, turnover=8530153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T14:15:03+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=0.379000, depth_time=2026-11-03T14:15:35+00:00, book20_bid_proxy_usdt=4699183, book20_ask_proxy_usdt=3311924, funding_indicative=-0.000071, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=48938913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T14:15:04+00:00, last15m_closed_end=2026-11-03T14:15+00:00, prior8high=0.065540, depth_time=2026-11-03T14:15:16+00:00, book20_bid_proxy_usdt=554673, book20_ask_proxy_usdt=343261, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.25%, turnover=11476551. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
