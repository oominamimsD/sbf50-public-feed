# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T01:15:31Z**
- feed_generated_utc: 2026-10-31T01:15:33+00:00
- source_sha256: `0a5e59c887ab1492a53c34effbe168b9fe8953fdaeb1b62e017f52c0111c6f21`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T01:15+00:00, close=77489.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T01:00+00:00, close=77521.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012950|-31.55|-62.99|-31.44|6048678|3.86|
|Q_USDT|0.037990|-19.98|-67.89|-19.87|18936053|7.92|
|EVAA_USDT|1.128200|-12.00|114.93|-11.89|6579178|8.86|
|BTW_USDT|1.126100|-6.11|-33.85|-6.00|9547439|0.89|
|BLESS_USDT|0.009351|-5.07|14.58|-4.96|12382932|1.07|
|BEAT_USDT|0.099960|-4.93|37.70|-4.82|8305688|3.00|
|TRX_USDT|0.323860|-3.46|-1.66|-3.35|8633553|2.16|
|HYPE_USDT|89.431000|-3.15|14.06|-3.04|129018665|0.11|
|LIT_USDT|2.757700|-2.35|-17.03|-2.24|6785095|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012950|0.013166|0.012952|1.89|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.099960|0.103920|0.099960|5.06|Y|N/N|N/N|Y|N|
|BLESS_USDT|0.009351|0.009456|0.009351|2.17|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|1.126100|1.108300|1.126100|0.58|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.128200|1.114800|1.128600|1.20|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.431000|89.059000|89.431000|0.84|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.757700|2.731800|2.757700|3.05|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.037990|0.041330|0.037990|7.87|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.323860|0.322780|0.323860|3.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T01:15:00+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=0.014277, depth_time=2026-10-31T01:15:08+00:00, book20_bid_proxy_usdt=5923, book20_ask_proxy_usdt=7221, funding_indicative=0.000027, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-31.55%, turnover=6048678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T01:15:00+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=0.106950, depth_time=2026-10-31T01:15:21+00:00, book20_bid_proxy_usdt=10065, book20_ask_proxy_usdt=10344, funding_indicative=0.000255, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=8305688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T01:14:59+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=0.009963, depth_time=2026-10-31T01:15:19+00:00, book20_bid_proxy_usdt=13801, book20_ask_proxy_usdt=18876, funding_indicative=0.000150, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.07%, turnover=12382932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T01:15:00+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=1.164800, depth_time=2026-10-31T01:15:16+00:00, book20_bid_proxy_usdt=18345, book20_ask_proxy_usdt=9131, funding_indicative=-0.000298, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.11%, turnover=9547439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T01:14:59+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=1.176200, depth_time=2026-10-31T01:15:13+00:00, book20_bid_proxy_usdt=6973, book20_ask_proxy_usdt=3604, funding_indicative=0.000117, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.00%, turnover=6579178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T01:14:59+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=90.278000, depth_time=2026-10-31T01:15:27+00:00, book20_bid_proxy_usdt=55343, book20_ask_proxy_usdt=144764, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=129018665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T01:15:00+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=2.784400, depth_time=2026-10-31T01:15:27+00:00, book20_bid_proxy_usdt=25810, book20_ask_proxy_usdt=21024, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=6785095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T01:14:59+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=0.049970, depth_time=2026-10-31T01:15:11+00:00, book20_bid_proxy_usdt=14727, book20_ask_proxy_usdt=29711, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.98%, turnover=18936053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T01:14:59+00:00, last15m_closed_end=2026-10-31T01:15+00:00, prior8high=0.331360, depth_time=2026-10-31T01:15:24+00:00, book20_bid_proxy_usdt=74603, book20_ask_proxy_usdt=69557, funding_indicative=-0.000985, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=8633553. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
