# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T21:45:18Z**
- feed_generated_utc: 2026-10-14T21:45:20+00:00
- source_sha256: `64564c868c99b67fec6e61f8caed5c93229248348918b4bbc14ba7eb7b0b75dd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T21:45+00:00, close=81787.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T21:00+00:00, close=81735.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.197100|-3.33|-12.98|-3.55|11080656|5.07|
|S_USDT|0.053290|-2.73|33.76|-2.95|5749729|1.88|
|BAT_USDT|0.169990|-2.53|71.43|-2.75|29807957|0.59|
|LDO_USDT|0.398900|-1.70|-6.66|-1.92|5094005|2.51|
|AAVE_USDT|153.980000|-1.22|-10.35|-1.44|25479873|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.980000|153.400000|153.990000|1.52|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169990|0.167120|0.169990|1.08|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.197100|0.192700|0.197100|0.69|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.398900|0.394500|0.399000|7.90|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053290|0.052560|0.053290|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T21:45:01+00:00, last15m_closed_end=2026-10-14T21:45+00:00, prior8high=155.360000, depth_time=2026-10-14T21:45:17+00:00, book20_bid_proxy_usdt=206649, book20_ask_proxy_usdt=224406, funding_indicative=0.000079, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=25479873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T21:45:01+00:00, last15m_closed_end=2026-10-14T21:45+00:00, prior8high=0.172860, depth_time=2026-10-14T21:45:11+00:00, book20_bid_proxy_usdt=38351, book20_ask_proxy_usdt=43885, funding_indicative=0.000038, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=29807957. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T21:45:01+00:00, last15m_closed_end=2026-10-14T21:45+00:00, prior8high=0.198400, depth_time=2026-10-14T21:45:08+00:00, book20_bid_proxy_usdt=944617, book20_ask_proxy_usdt=937925, funding_indicative=0.000021, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=11080656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T21:45:01+00:00, last15m_closed_end=2026-10-14T21:45+00:00, prior8high=0.404100, depth_time=2026-10-14T21:45:14+00:00, book20_bid_proxy_usdt=637221, book20_ask_proxy_usdt=423225, funding_indicative=-0.000094, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=5094005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T21:45:01+00:00, last15m_closed_end=2026-10-14T21:45+00:00, prior8high=0.053720, depth_time=2026-10-14T21:45:08+00:00, book20_bid_proxy_usdt=136015, book20_ask_proxy_usdt=166796, funding_indicative=-0.000082, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=5749729. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
