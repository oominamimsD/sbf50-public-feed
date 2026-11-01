# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T05:15:30Z**
- feed_generated_utc: 2026-11-01T05:15:32+00:00
- source_sha256: `c5e5a55a9e816e1c19e7ad9b109d68df5b87e2bb7c35453065e40a8e56fc2575`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T05:15+00:00, close=77798.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T05:00+00:00, close=77770.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244510|-17.43|45.61|-17.73|30547501|0.41|
|AKE_USDT|0.009601|-13.79|-67.15|-14.09|11623975|4.17|
|BLESS_USDT|0.009459|-10.46|16.59|-10.76|6507975|5.29|
|XPL_USDT|0.073500|-9.60|1.78|-9.90|5019504|1.36|
|ENA_USDT|0.187780|-3.21|0.53|-3.51|42868407|0.53|
|ZEC_USDT|1248.350000|-2.81|9.00|-3.11|949635562|0.08|
|XLM_USDT|0.168740|-1.74|0.19|-2.04|20102132|0.59|
|BEAT_USDT|0.097250|-1.30|45.12|-1.60|6015030|5.14|
|TRX_USDT|0.309740|-0.82|-5.83|-1.12|10816295|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009601|0.008443|0.009591|1.15|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097250|0.097020|0.097200|0.79|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009459|0.009250|0.009456|1.84|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187780|0.185670|0.187780|2.30|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.244510|0.226590|0.245570|0.99|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.309740|0.307330|0.309720|0.43|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168740|0.167510|0.168740|0.84|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.073500|0.069100|0.073710|55.29|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1248.350000|1238.800000|1248.230000|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.009935, depth_time=2026-11-01T05:15:10+00:00, book20_bid_proxy_usdt=7576, book20_ask_proxy_usdt=8638, funding_indicative=-0.003490, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.79%, turnover=11623975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.099240, depth_time=2026-11-01T05:15:26+00:00, book20_bid_proxy_usdt=7146, book20_ask_proxy_usdt=15741, funding_indicative=0.000232, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=6015030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.009822, depth_time=2026-11-01T05:15:13+00:00, book20_bid_proxy_usdt=7844, book20_ask_proxy_usdt=16619, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=6507975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.189100, depth_time=2026-11-01T05:15:19+00:00, book20_bid_proxy_usdt=63709, book20_ask_proxy_usdt=126044, funding_indicative=-0.000002, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=42868407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.244560, depth_time=2026-11-01T05:15:08+00:00, book20_bid_proxy_usdt=7226, book20_ask_proxy_usdt=10116, funding_indicative=-0.001877, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.43%, turnover=30547501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.309780, depth_time=2026-11-01T05:15:26+00:00, book20_bid_proxy_usdt=188484, book20_ask_proxy_usdt=151845, funding_indicative=-0.000867, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=10816295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.169260, depth_time=2026-11-01T05:15:24+00:00, book20_bid_proxy_usdt=134996, book20_ask_proxy_usdt=138963, funding_indicative=0.000060, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=20102132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=0.086230, depth_time=2026-11-01T05:15:16+00:00, book20_bid_proxy_usdt=317426, book20_ask_proxy_usdt=312864, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.60%, turnover=5019504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T05:15:02+00:00, last15m_closed_end=2026-11-01T05:15+00:00, prior8high=1251.980000, depth_time=2026-11-01T05:15:21+00:00, book20_bid_proxy_usdt=159780, book20_ask_proxy_usdt=952146, funding_indicative=-0.000132, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=949635562. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
