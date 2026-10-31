# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T07:30:32Z**
- feed_generated_utc: 2026-10-31T07:30:34+00:00
- source_sha256: `28c3d00eb4b30d4398ffb59bcb4a086d7e8da163be754ca7b6d5a17b8b0914c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T07:30+00:00, close=77386.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T07:00+00:00, close=77350.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013021|-31.18|-62.79|-30.94|7151054|4.61|
|BEAT_USDT|0.098100|-6.70|35.14|-6.46|8478513|2.04|
|EVAA_USDT|1.199800|-6.41|128.57|-6.17|5813374|3.34|
|HYPE_USDT|88.581000|-4.07|12.98|-3.83|106354545|0.11|
|TRX_USDT|0.323000|-3.72|-1.92|-3.48|6012471|0.31|
|BTW_USDT|1.162400|-3.09|-31.71|-2.85|9500987|0.86|
|WLD_USDT|0.399600|-2.98|-24.94|-2.74|48065647|2.50|
|ZRO_USDT|1.699100|-2.89|-6.09|-2.65|5460472|1.77|
|DASH_USDT|47.950000|-2.22|-10.95|-1.98|14199175|2.09|
|FET_USDT|0.163100|-2.10|-12.92|-1.86|6244035|6.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013021|0.010878|0.012987|1.24|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098100|0.096280|0.098100|0.46|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.162400|1.108600|1.162400|0.73|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.950000|47.870000|47.950000|1.54|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.199800|1.168700|1.199800|1.27|N|Y/Y|N/N|Y|N|
|FET_USDT|0.163100|0.162200|0.163100|1.26|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.581000|88.038000|88.585000|0.53|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.323000|0.323650|0.323000|1.09|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399600|0.394700|0.399700|0.52|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.699100|1.688700|1.698800|6.86|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=0.012789, depth_time=2026-10-31T07:30:08+00:00, book20_bid_proxy_usdt=7416, book20_ask_proxy_usdt=4778, funding_indicative=-0.000094, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.18%, turnover=7151054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=0.098520, depth_time=2026-10-31T07:30:09+00:00, book20_bid_proxy_usdt=14600, book20_ask_proxy_usdt=12940, funding_indicative=0.000178, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.70%, turnover=8478513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=1.176000, depth_time=2026-10-31T07:30:21+00:00, book20_bid_proxy_usdt=14345, book20_ask_proxy_usdt=22604, funding_indicative=-0.000621, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=9500987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=48.190000, depth_time=2026-10-31T07:30:28+00:00, book20_bid_proxy_usdt=1000785, book20_ask_proxy_usdt=686426, funding_indicative=0.000072, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=14199175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=1.242000, depth_time=2026-10-31T07:30:13+00:00, book20_bid_proxy_usdt=15617, book20_ask_proxy_usdt=3244, funding_indicative=0.000252, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=5813374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=0.164200, depth_time=2026-10-31T07:30:31+00:00, book20_bid_proxy_usdt=1211626, book20_ask_proxy_usdt=703722, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=6244035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=89.040000, depth_time=2026-10-31T07:30:14+00:00, book20_bid_proxy_usdt=92576, book20_ask_proxy_usdt=130266, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.07%, turnover=106354545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=0.326220, depth_time=2026-10-31T07:30:16+00:00, book20_bid_proxy_usdt=718080, book20_ask_proxy_usdt=86514, funding_indicative=-0.000530, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=6012471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=0.401700, depth_time=2026-10-31T07:30:22+00:00, book20_bid_proxy_usdt=3692245, book20_ask_proxy_usdt=3010636, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=48065647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-31T07:30:03+00:00, last15m_closed_end=2026-10-31T07:30+00:00, prior8high=1.728600, depth_time=2026-10-31T07:30:25+00:00, book20_bid_proxy_usdt=33500, book20_ask_proxy_usdt=23883, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=5460472. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
