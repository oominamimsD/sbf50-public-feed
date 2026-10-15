# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T00:15:15Z**
- feed_generated_utc: 2026-10-15T00:15:16+00:00
- source_sha256: `d03a24214f6283ed7d5057673f854297c00b8843d75f616f519ae2844dcf5d8c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T00:15+00:00, close=81772.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.198600|-2.59|-12.31|-2.80|10727430|5.04|
|S_USDT|0.054120|-1.22|35.84|-1.43|5185196|1.85|
|AAVE_USDT|154.090000|-1.15|-10.28|-1.36|25952679|0.65|
|LDO_USDT|0.402200|-0.88|-5.89|-1.09|5107208|7.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.090000|152.860000|154.090000|0.55|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.198600|0.196400|0.198600|0.63|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.402200|0.398500|0.402100|2.19|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.054120|0.052790|0.054120|0.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T00:15:00+00:00, last15m_closed_end=2026-10-15T00:15+00:00, prior8high=154.420000, depth_time=2026-10-15T00:15:11+00:00, book20_bid_proxy_usdt=332942, book20_ask_proxy_usdt=254536, funding_indicative=0.000070, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=25952679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T00:15:00+00:00, last15m_closed_end=2026-10-15T00:15+00:00, prior8high=0.198600, depth_time=2026-10-15T00:15:07+00:00, book20_bid_proxy_usdt=900238, book20_ask_proxy_usdt=802540, funding_indicative=0.000070, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=10727430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-15T00:15:01+00:00, last15m_closed_end=2026-10-15T00:15+00:00, prior8high=0.402400, depth_time=2026-10-15T00:15:13+00:00, book20_bid_proxy_usdt=673066, book20_ask_proxy_usdt=507825, funding_indicative=-0.000054, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=5107208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-15T00:15:01+00:00, last15m_closed_end=2026-10-15T00:15+00:00, prior8high=0.054240, depth_time=2026-10-15T00:15:09+00:00, book20_bid_proxy_usdt=151456, book20_ask_proxy_usdt=162534, funding_indicative=-0.000109, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=5185196. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
