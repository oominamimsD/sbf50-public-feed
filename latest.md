# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T18:30:27Z**
- feed_generated_utc: 2026-10-28T18:30:31+00:00
- source_sha256: `0354dc949a737bf75cf6c5f0bae80c998bd0158bb148b891bd7fb624f7e31f44`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T18:30+00:00, close=80901.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T18:00+00:00, close=80827.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.142840|-5.15|256.65|-5.63|7873368|2.80|
|APR_USDT|0.047620|-2.65|73.66|-3.13|5107348|8.40|
|TIA_USDT|0.530300|-1.81|-16.15|-2.29|15004912|1.89|
|STRK_USDT|0.046090|-1.51|-25.62|-1.99|5176751|2.17|
|HBAR_USDT|0.074900|-1.33|-12.84|-1.81|12068935|1.33|
|ONDO_USDT|0.415500|-0.88|-10.95|-1.36|17186490|2.41|
|APT_USDT|0.682700|-0.87|-18.29|-1.35|6381184|1.46|
|XMR_USDT|599.460000|-0.76|0.54|-1.24|5530051|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.142840|0.143170|0.142610|0.47|N|Y/N|N/N|N|N|
|APR_USDT|0.047620|0.047990|0.047610|0.56|N|N/N|N/N|N|N|
|APT_USDT|0.682700|0.675400|0.682700|0.25|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.074900|0.074610|0.074900|1.21|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.415500|0.412000|0.415100|1.63|N|Y/Y|N/N|N|N|
|STRK_USDT|0.046090|0.045520|0.046090|0.74|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.530300|0.522800|0.529700|0.63|N|Y/Y|N/Y|N|N|
|XMR_USDT|599.460000|598.000000|599.320000|0.26|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T18:30:03+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.149850, depth_time=2026-10-28T18:30:08+00:00, book20_bid_proxy_usdt=9408, book20_ask_proxy_usdt=14705, funding_indicative=0.000659, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=7873368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APR_USDT: quote_utc=2026-10-28T18:30:03+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.051020, depth_time=2026-10-28T18:30:11+00:00, book20_bid_proxy_usdt=41458, book20_ask_proxy_usdt=50494, funding_indicative=0.000143, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=5107348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-28T18:30:04+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.687600, depth_time=2026-10-28T18:30:23+00:00, book20_bid_proxy_usdt=84024, book20_ask_proxy_usdt=128420, funding_indicative=-0.000144, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.87%, turnover=6381184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T18:30:04+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.075700, depth_time=2026-10-28T18:30:19+00:00, book20_bid_proxy_usdt=486429, book20_ask_proxy_usdt=1056173, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=12068935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T18:30:04+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.419300, depth_time=2026-10-28T18:30:20+00:00, book20_bid_proxy_usdt=1546337, book20_ask_proxy_usdt=1085258, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=17186490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T18:30:04+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.046420, depth_time=2026-10-28T18:30:16+00:00, book20_bid_proxy_usdt=592126, book20_ask_proxy_usdt=649050, funding_indicative=-0.000021, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=5176751. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T18:30:04+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=0.537800, depth_time=2026-10-28T18:30:13+00:00, book20_bid_proxy_usdt=213491, book20_ask_proxy_usdt=303551, funding_indicative=0.000027, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=15004912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T18:30:04+00:00, last15m_closed_end=2026-10-28T18:30+00:00, prior8high=608.380000, depth_time=2026-10-28T18:30:26+00:00, book20_bid_proxy_usdt=14148, book20_ask_proxy_usdt=23482, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=5530051. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
