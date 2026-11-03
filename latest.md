# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T15:30:33Z**
- feed_generated_utc: 2026-11-03T15:30:36+00:00
- source_sha256: `7db1d1ca70aa00c19cf04a2dab4731ee0ab93631e122378b663d72ee60adabea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T15:30+00:00, close=77335.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T15:00+00:00, close=77364.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004130|-24.93|-86.58|-24.76|12521727|2.42|
|UAI_USDT|0.103500|-22.00|-58.40|-21.83|9290935|9.67|
|XPL_USDT|0.063890|-8.17|-13.99|-8.00|11219211|1.57|
|BEAT_USDT|0.093070|-7.15|14.44|-6.98|7949586|2.15|
|TIA_USDT|0.434400|-4.92|-18.90|-4.75|13649713|2.30|
|NEAR_USDT|3.845000|-4.11|-15.91|-3.94|81541726|2.60|
|QNT_USDT|194.440000|-3.95|-7.53|-3.78|54513546|3.60|
|DASH_USDT|45.850000|-2.86|-12.19|-2.69|8750650|2.18|
|ENA_USDT|0.170100|-2.82|-19.14|-2.65|70257154|0.59|
|WLD_USDT|0.370600|-2.78|-16.71|-2.61|49218026|2.70|
|LINK_USDT|11.101000|-1.18|-3.70|-1.01|175100136|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004130|0.003997|0.004130|1.44|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.093070|0.095500|0.093070|2.70|Y|Y/Y|N/N|Y|N|
|DASH_USDT|45.850000|45.970000|45.860000|1.12|N|Y/N|Y/Y|Y|N|
|ENA_USDT|0.170100|0.169280|0.170100|0.99|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.101000|11.136000|11.100000|1.58|Y|N/N|Y/Y|Y|N|
|NEAR_USDT|3.845000|3.841000|3.845000|1.48|N|Y/N|Y/Y|Y|N|
|QNT_USDT|194.440000|193.330000|194.440000|1.02|N|Y/N|Y/Y|Y|N|
|TIA_USDT|0.434400|0.435400|0.433900|1.44|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.103500|0.096800|0.103500|0.87|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.370600|0.370700|0.370400|2.28|Y|Y/N|Y/Y|Y|N|
|XPL_USDT|0.063890|0.064020|0.063890|1.68|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.004336, depth_time=2026-11-03T15:30:06+00:00, book20_bid_proxy_usdt=43430, book20_ask_proxy_usdt=29088, funding_indicative=-0.000200, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.93%, turnover=12521727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.104140, depth_time=2026-11-03T15:30:15+00:00, book20_bid_proxy_usdt=22563, book20_ask_proxy_usdt=16298, funding_indicative=0.000336, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.15%, turnover=7949586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=46.820000, depth_time=2026-11-03T15:30:24+00:00, book20_bid_proxy_usdt=744759, book20_ask_proxy_usdt=787414, funding_indicative=0.000092, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=8750650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.174220, depth_time=2026-11-03T15:30:28+00:00, book20_bid_proxy_usdt=135808, book20_ask_proxy_usdt=193723, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=70257154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=11.308000, depth_time=2026-11-03T15:30:32+00:00, book20_bid_proxy_usdt=289138, book20_ask_proxy_usdt=866870, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=175100136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=3.945000, depth_time=2026-11-03T15:30:20+00:00, book20_bid_proxy_usdt=550762, book20_ask_proxy_usdt=3375060, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.11%, turnover=81541726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=200.480000, depth_time=2026-11-03T15:30:23+00:00, book20_bid_proxy_usdt=69503, book20_ask_proxy_usdt=70335, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=54513546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.448700, depth_time=2026-11-03T15:30:18+00:00, book20_bid_proxy_usdt=306098, book20_ask_proxy_usdt=385328, funding_indicative=-0.000022, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.92%, turnover=13649713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.172500, depth_time=2026-11-03T15:30:10+00:00, book20_bid_proxy_usdt=170939, book20_ask_proxy_usdt=179094, funding_indicative=-0.000231, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.00%, turnover=9290935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.378300, depth_time=2026-11-03T15:30:30+00:00, book20_bid_proxy_usdt=2123624, book20_ask_proxy_usdt=4598558, funding_indicative=0.000011, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=49218026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T15:30:02+00:00, last15m_closed_end=2026-11-03T15:30+00:00, prior8high=0.065420, depth_time=2026-11-03T15:30:13+00:00, book20_bid_proxy_usdt=357872, book20_ask_proxy_usdt=534170, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.17%, turnover=11219211. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
