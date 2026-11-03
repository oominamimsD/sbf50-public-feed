# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T20:30:20Z**
- feed_generated_utc: 2026-11-03T20:30:22+00:00
- source_sha256: `c1fd98fd7cb4f5be57f79115ddf3c836bae7e9c452b43d3a8f1b679c62980da5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T20:30+00:00, close=77756, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|191.480000|-2.01|-3.23|-2.12|57366081|0.52|
|TRUMPOFFICIAL_USDT|1.578000|-1.86|-6.51|-1.97|5956913|6.34|
|XLM_USDT|0.162680|-1.28|-3.85|-1.39|33498784|0.61|
|OP_USDT|0.109020|-1.27|-2.06|-1.38|8800526|0.92|
|TIA_USDT|0.431400|-1.00|-19.52|-1.11|11780866|2.32|
|HBAR_USDT|0.069380|-0.92|-8.85|-1.03|5543339|1.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|HBAR_USDT|0.069380|0.069140|0.069390|0.52|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109020|0.108650|0.108940|0.88|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.480000|190.330000|191.670000|0.64|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.431400|0.427600|0.431400|0.38|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.578000|1.571000|1.578000|0.45|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162680|0.162310|0.162670|0.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- HBAR_USDT: quote_utc=2026-11-03T20:30:01+00:00, last15m_closed_end=2026-11-03T20:30+00:00, prior8high=0.069890, depth_time=2026-11-03T20:30:20+00:00, book20_bid_proxy_usdt=1065442, book20_ask_proxy_usdt=1135708, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=5543339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T20:30:01+00:00, last15m_closed_end=2026-11-03T20:30+00:00, prior8high=0.110950, depth_time=2026-11-03T20:30:15+00:00, book20_bid_proxy_usdt=133325, book20_ask_proxy_usdt=138542, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=8800526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T20:30:01+00:00, last15m_closed_end=2026-11-03T20:30+00:00, prior8high=194.680000, depth_time=2026-11-03T20:30:07+00:00, book20_bid_proxy_usdt=64640, book20_ask_proxy_usdt=35771, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=57366081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T20:30:01+00:00, last15m_closed_end=2026-11-03T20:30+00:00, prior8high=0.433900, depth_time=2026-11-03T20:30:17+00:00, book20_bid_proxy_usdt=344066, book20_ask_proxy_usdt=363401, funding_indicative=-0.000031, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=11780866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T20:30:01+00:00, last15m_closed_end=2026-11-03T20:30+00:00, prior8high=1.588000, depth_time=2026-11-03T20:30:10+00:00, book20_bid_proxy_usdt=1972257, book20_ask_proxy_usdt=1814452, funding_indicative=0.000027, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=5956913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T20:30:01+00:00, last15m_closed_end=2026-11-03T20:30+00:00, prior8high=0.164650, depth_time=2026-11-03T20:30:13+00:00, book20_bid_proxy_usdt=224945, book20_ask_proxy_usdt=201601, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=33498784. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
