# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T06:00:38Z**
- feed_generated_utc: 2026-10-13T06:00:41+00:00
- source_sha256: `35cd75c9e72b5e3f206daa0124b6469db64301b9f233d3694dbd59b896366028`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T06:00+00:00, close=83646.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T06:00+00:00, close=83646.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.019370|-19.83|36.95|-20.98|34214483|0.52|
|DOS_USDT|0.234800|-18.89|10.23|-20.04|9280865|4.26|
|RLC_USDT|0.954200|-7.05|74.12|-8.20|6852762|1.05|
|ZRO_USDT|2.113400|-6.52|3.31|-7.67|29334250|0.47|
|PUMPFUN_USDT|0.005106|-5.89|-19.40|-7.04|30672860|1.96|
|LIT_USDT|3.458800|-4.59|-9.02|-5.74|10575043|0.29|
|STRK_USDT|0.086780|-4.29|66.53|-5.44|63505637|2.31|
|ICP_USDT|3.180000|-3.98|-8.25|-5.13|16798149|3.15|
|ENA_USDT|0.214800|-3.09|-12.53|-4.24|67514537|0.47|
|PONS_USDT|0.291400|-2.60|-24.01|-3.75|6253783|3.43|
|HBAR_USDT|0.088060|-2.55|-12.55|-3.70|22033941|1.14|
|GRASS_USDT|0.770400|0.02|9.24|-1.13|6560857|1.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.234800|0.227700|0.235200|0.38|N|Y/Y|Y/N|N|N|
|ENA_USDT|0.214800|0.210600|0.215000|0.69|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.770400|0.760500|0.770400|0.48|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.088060|0.087260|0.088060|0.18|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.180000|3.131000|3.180000|0.56|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.458800|3.414500|3.458000|0.40|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.291400|0.281000|0.291400|0.83|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005106|0.005026|0.005106|1.19|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.954200|0.939400|0.954200|0.29|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.086780|0.082590|0.086840|0.25|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019370|0.018901|0.019370|0.33|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.113400|2.098900|2.114700|1.18|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.251000, depth_time=2026-10-13T06:00:10+00:00, book20_bid_proxy_usdt=61070, book20_ask_proxy_usdt=80024, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.89%, turnover=9280865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.214970, depth_time=2026-10-13T06:00:29+00:00, book20_bid_proxy_usdt=126470, book20_ask_proxy_usdt=89884, funding_indicative=-0.000025, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=67514537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.781400, depth_time=2026-10-13T06:00:37+00:00, book20_bid_proxy_usdt=88186, book20_ask_proxy_usdt=181936, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.02%, turnover=6560857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.088580, depth_time=2026-10-13T06:00:34+00:00, book20_bid_proxy_usdt=508386, book20_ask_proxy_usdt=609637, funding_indicative=0.000007, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=22033941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=3.205000, depth_time=2026-10-13T06:00:26+00:00, book20_bid_proxy_usdt=876744, book20_ask_proxy_usdt=796143, funding_indicative=-0.000051, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=16798149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T06:00:03+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=3.476600, depth_time=2026-10-13T06:00:21+00:00, book20_bid_proxy_usdt=37957, book20_ask_proxy_usdt=41468, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.59%, turnover=10575043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T06:00:03+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.290600, depth_time=2026-10-13T06:00:32+00:00, book20_bid_proxy_usdt=212238, book20_ask_proxy_usdt=216084, funding_indicative=0.000091, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=6253783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.005107, depth_time=2026-10-13T06:00:18+00:00, book20_bid_proxy_usdt=1582483, book20_ask_proxy_usdt=1513250, funding_indicative=0.000027, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=30672860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.964300, depth_time=2026-10-13T06:00:12+00:00, book20_bid_proxy_usdt=41590, book20_ask_proxy_usdt=61828, funding_indicative=-0.000544, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.05%, turnover=6852762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.089670, depth_time=2026-10-13T06:00:23+00:00, book20_bid_proxy_usdt=138109, book20_ask_proxy_usdt=165514, funding_indicative=0.000029, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=63505637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=0.019641, depth_time=2026-10-13T06:00:08+00:00, book20_bid_proxy_usdt=26631, book20_ask_proxy_usdt=21956, funding_indicative=-0.000479, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.83%, turnover=34214483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T06:00:02+00:00, last15m_closed_end=2026-10-13T06:00+00:00, prior8high=2.149200, depth_time=2026-10-13T06:00:15+00:00, book20_bid_proxy_usdt=36480, book20_ask_proxy_usdt=31631, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.52%, turnover=29334250. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
