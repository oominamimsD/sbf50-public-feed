# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T21:30:19Z**
- feed_generated_utc: 2026-10-14T21:30:20+00:00
- source_sha256: `92bf9d6abf52aabe8c7135b30facafb608431c9a12359b311681eef4e4946608`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T21:30+00:00, close=81822.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T21:00+00:00, close=81735.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.167990|-3.68|69.41|-3.95|29697475|2.98|
|FET_USDT|0.197000|-3.38|-13.02|-3.65|10965203|5.07|
|S_USDT|0.053230|-2.84|33.60|-3.11|5734782|1.88|
|AAVE_USDT|153.940000|-1.25|-10.37|-1.52|24987662|0.65|
|STRK_USDT|0.076560|-0.80|54.79|-1.07|24828661|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.940000|153.400000|153.940000|1.30|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.167990|0.167120|0.167970|1.33|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.197000|0.192700|0.197000|0.60|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.076560|0.075110|0.076570|1.04|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053230|0.052560|0.053230|0.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T21:30:01+00:00, last15m_closed_end=2026-10-14T21:30+00:00, prior8high=155.360000, depth_time=2026-10-14T21:30:15+00:00, book20_bid_proxy_usdt=281659, book20_ask_proxy_usdt=253355, funding_indicative=0.000072, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=24987662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T21:30:01+00:00, last15m_closed_end=2026-10-14T21:30+00:00, prior8high=0.172860, depth_time=2026-10-14T21:30:08+00:00, book20_bid_proxy_usdt=25754, book20_ask_proxy_usdt=32480, funding_indicative=0.000028, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=29697475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T21:30:01+00:00, last15m_closed_end=2026-10-14T21:30+00:00, prior8high=0.199700, depth_time=2026-10-14T21:30:09+00:00, book20_bid_proxy_usdt=856688, book20_ask_proxy_usdt=1196654, funding_indicative=0.000049, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=10965203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T21:30:01+00:00, last15m_closed_end=2026-10-14T21:30+00:00, prior8high=0.078300, depth_time=2026-10-14T21:30:18+00:00, book20_bid_proxy_usdt=203148, book20_ask_proxy_usdt=396615, funding_indicative=0.000010, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.80%, turnover=24828661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T21:30:01+00:00, last15m_closed_end=2026-10-14T21:30+00:00, prior8high=0.053720, depth_time=2026-10-14T21:30:12+00:00, book20_bid_proxy_usdt=94535, book20_ask_proxy_usdt=156201, funding_indicative=-0.000087, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=5734782. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
