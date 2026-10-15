# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T01:45:22Z**
- feed_generated_utc: 2026-10-15T01:45:24+00:00
- source_sha256: `b4aabce837ad5a4796843ffbe49de4364467d8e21137b08989fb5c8e0759bb11`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T01:45+00:00, close=81809.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T01:00+00:00, close=81624.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.314700|-8.51|-23.33|-8.76|7040406|3.18|
|BAT_USDT|0.168610|-3.33|70.03|-3.58|23647847|1.78|
|FET_USDT|0.199100|-2.35|-12.09|-2.60|11048690|5.02|
|FARTCOIN_USDT|0.153630|-1.92|-4.08|-2.17|8022767|0.65|
|AAVE_USDT|153.860000|-1.30|-10.42|-1.55|26030132|0.65|
|STRK_USDT|0.076370|-1.04|54.40|-1.29|23574761|1.31|
|NEAR_USDT|4.803000|-0.78|-4.58|-1.03|180468549|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.860000|153.100000|153.860000|0.45|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.168610|0.166430|0.168610|0.28|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.153630|0.152860|0.153630|0.25|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.199100|0.196700|0.199100|1.20|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.803000|4.774000|4.803000|0.97|N|Y/Y|Y/Y|Y|N|
|PONS_USDT|0.314700|0.307900|0.314700|0.47|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.076370|0.076190|0.076370|0.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T01:45:00+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=154.480000, depth_time=2026-10-15T01:45:16+00:00, book20_bid_proxy_usdt=254942, book20_ask_proxy_usdt=254996, funding_indicative=0.000043, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=26030132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T01:44:59+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=0.178290, depth_time=2026-10-15T01:45:09+00:00, book20_bid_proxy_usdt=27068, book20_ask_proxy_usdt=25517, funding_indicative=0.000006, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=23647847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T01:45:00+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=0.156150, depth_time=2026-10-15T01:45:13+00:00, book20_bid_proxy_usdt=43874, book20_ask_proxy_usdt=52856, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=8022767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T01:45:00+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=0.200300, depth_time=2026-10-15T01:45:11+00:00, book20_bid_proxy_usdt=1043718, book20_ask_proxy_usdt=1052045, funding_indicative=-0.000042, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=11048690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-15T01:44:59+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=4.925000, depth_time=2026-10-15T01:45:20+00:00, book20_bid_proxy_usdt=1220706, book20_ask_proxy_usdt=244046, funding_indicative=0.000100, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=180468549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T01:45:00+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=0.333100, depth_time=2026-10-15T01:45:06+00:00, book20_bid_proxy_usdt=148325, book20_ask_proxy_usdt=189849, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.51%, turnover=7040406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-15T01:45:00+00:00, last15m_closed_end=2026-10-15T01:45+00:00, prior8high=0.077900, depth_time=2026-10-15T01:45:18+00:00, book20_bid_proxy_usdt=322031, book20_ask_proxy_usdt=309114, funding_indicative=0.000025, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=23574761. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
