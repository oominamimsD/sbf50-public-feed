# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T19:30:43Z**
- feed_generated_utc: 2026-10-29T19:30:45+00:00
- source_sha256: `07ef69cf22556f1b2b08de53e16f7c6e502703215ba1e3b7a288bf9a450f186d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T19:30+00:00, close=80794, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T19:00+00:00, close=80824.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.480600|-9.61|-17.28|-8.47|9795439|5.40|
|NEAR_USDT|4.405000|-5.24|-10.90|-4.10|113193872|2.27|
|PENGU_USDT|0.007707|-5.21|-0.27|-4.07|6754679|1.30|
|APT_USDT|0.670600|-4.64|-13.15|-3.50|9651654|2.98|
|WLD_USDT|0.417500|-4.30|-21.53|-3.16|83515091|2.40|
|Q_USDT|0.036770|-4.26|-71.46|-3.12|25356453|2.72|
|FARTCOIN_USDT|0.128900|-4.09|-9.75|-2.95|10727616|0.78|
|TRUMPOFFICIAL_USDT|1.659000|-3.99|-4.87|-2.85|6389222|6.03|
|FET_USDT|0.177700|-3.84|-4.10|-2.70|9510857|5.63|
|QNT_USDT|191.120000|-3.83|0.21|-2.69|63294719|0.52|
|ARB_USDT|0.168220|-3.57|-8.39|-2.43|26340363|0.59|
|OP_USDT|0.110010|-3.42|-8.21|-2.28|6769953|1.82|
|DOT_USDT|0.983900|-3.29|-12.48|-2.15|10370633|1.02|
|SEI_USDT|0.051700|-3.25|-10.96|-2.11|5377878|1.93|
|FILECOIN_USDT|0.892000|-2.83|-7.27|-1.69|9676898|1.12|
|HBAR_USDT|0.073190|-2.76|-8.63|-1.62|15152870|1.37|
|ICP_USDT|2.555000|-2.74|-6.98|-1.60|5418316|3.92|
|SOL_USDT|100.190000|-2.38|-4.19|-1.24|638881583|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.670600|0.666900|0.670600|0.91|N|Y/N|N/Y|N|N|
|ARB_USDT|0.168220|0.167330|0.168220|0.48|N|Y/N|N/Y|N|N|
|BTW_USDT|1.480600|1.464400|1.480100|0.78|N|Y/Y|Y/N|N|N|
|DOT_USDT|0.983900|0.977200|0.983900|1.81|N|Y/Y|N/Y|N|N|
|FARTCOIN_USDT|0.128900|0.128550|0.128900|0.49|N|Y/N|N/Y|N|N|
|FET_USDT|0.177700|0.176800|0.177700|0.56|N|Y/Y|N/N|N|N|
|FILECOIN_USDT|0.892000|0.887600|0.892000|0.30|N|Y/Y|N/Y|N|N|
|NEAR_USDT|4.405000|4.381000|4.405000|0.99|N|Y/Y|N/Y|N|N|
|OP_USDT|0.110010|0.109470|0.110010|0.24|N|Y/N|N/Y|N|N|
|PENGU_USDT|0.007707|0.007703|0.007707|0.66|N|Y/N|N/N|N|N|
|QNT_USDT|191.120000|188.850000|191.120000|0.25|N|Y/Y|N/Y|N|N|
|Q_USDT|0.036770|0.035730|0.036770|1.08|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.051700|0.051390|0.051700|0.28|N|Y/Y|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.659000|1.656000|1.659000|2.07|N|Y/Y|N/Y|N|N|
|WLD_USDT|0.417500|0.415700|0.417500|0.62|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.689500, depth_time=2026-10-29T19:30:15+00:00, book20_bid_proxy_usdt=136388, book20_ask_proxy_usdt=151051, funding_indicative=0.000080, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.64%, turnover=9651654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.171860, depth_time=2026-10-29T19:30:32+00:00, book20_bid_proxy_usdt=67900, book20_ask_proxy_usdt=168509, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.57%, turnover=26340363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=1.560600, depth_time=2026-10-29T19:30:07+00:00, book20_bid_proxy_usdt=15950, book20_ask_proxy_usdt=15232, funding_indicative=0.000016, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.61%, turnover=9795439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=1.004300, depth_time=2026-10-29T19:30:37+00:00, book20_bid_proxy_usdt=101631, book20_ask_proxy_usdt=633962, funding_indicative=0.000081, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=10370633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.132790, depth_time=2026-10-29T19:30:23+00:00, book20_bid_proxy_usdt=47214, book20_ask_proxy_usdt=65057, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.09%, turnover=10727616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.182200, depth_time=2026-10-29T19:30:26+00:00, book20_bid_proxy_usdt=1320914, book20_ask_proxy_usdt=839501, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=9510857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.908700, depth_time=2026-10-29T19:30:41+00:00, book20_bid_proxy_usdt=1072851, book20_ask_proxy_usdt=1317522, funding_indicative=0.000063, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.83%, turnover=9676898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T19:29:59+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=4.582000, depth_time=2026-10-29T19:30:10+00:00, book20_bid_proxy_usdt=3923116, book20_ask_proxy_usdt=6198785, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=113193872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.112470, depth_time=2026-10-29T19:30:35+00:00, book20_bid_proxy_usdt=94007, book20_ask_proxy_usdt=125198, funding_indicative=0.000001, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=6769953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.007973, depth_time=2026-10-29T19:30:12+00:00, book20_bid_proxy_usdt=183282, book20_ask_proxy_usdt=176692, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=6754679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=195.590000, depth_time=2026-10-29T19:30:30+00:00, book20_bid_proxy_usdt=99937, book20_ask_proxy_usdt=82840, funding_indicative=-0.000108, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=63294719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T19:29:59+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.038780, depth_time=2026-10-29T19:30:21+00:00, book20_bid_proxy_usdt=65287, book20_ask_proxy_usdt=50879, funding_indicative=0.000038, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=25356453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.052850, depth_time=2026-10-29T19:30:38+00:00, book20_bid_proxy_usdt=197000, book20_ask_proxy_usdt=262982, funding_indicative=0.000066, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=5377878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=1.702000, depth_time=2026-10-29T19:30:23+00:00, book20_bid_proxy_usdt=2450366, book20_ask_proxy_usdt=1775922, funding_indicative=0.000015, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=6389222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T19:30:00+00:00, last15m_closed_end=2026-10-29T19:30+00:00, prior8high=0.431200, depth_time=2026-10-29T19:30:18+00:00, book20_bid_proxy_usdt=3974630, book20_ask_proxy_usdt=3797254, funding_indicative=0.000017, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=83515091. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
