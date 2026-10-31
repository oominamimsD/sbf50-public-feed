# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T18:15:16Z**
- feed_generated_utc: 2026-10-31T18:15:18+00:00
- source_sha256: `1917c8d12fd94e47ff6d2560b76e31b61062b75589f63dd9809cd17a9faefc72`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T18:15+00:00, close=77676, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T18:00+00:00, close=77664.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRX_USDT|0.307370|-1.58|-6.55|-1.72|6962868|0.33|
|WLD_USDT|0.399800|-1.13|-13.46|-1.27|38110510|2.50|
|FET_USDT|0.161500|-1.10|-6.26|-1.24|5800101|6.19|
|BTW_USDT|1.110100|-1.05|-36.24|-1.19|7269769|6.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.110100|1.083700|1.110100|0.99|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161500|0.161200|0.161500|0.17|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.307370|0.306900|0.307250|1.71|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399800|0.397400|0.399800|0.71|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T18:15:02+00:00, last15m_closed_end=2026-10-31T18:15+00:00, prior8high=1.127900, depth_time=2026-10-31T18:15:15+00:00, book20_bid_proxy_usdt=15629, book20_ask_proxy_usdt=11771, funding_indicative=-0.000304, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=7269769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T18:15:02+00:00, last15m_closed_end=2026-10-31T18:15+00:00, prior8high=0.163400, depth_time=2026-10-31T18:15:12+00:00, book20_bid_proxy_usdt=1429953, book20_ask_proxy_usdt=765840, funding_indicative=-0.000009, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=5800101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T18:15:02+00:00, last15m_closed_end=2026-10-31T18:15+00:00, prior8high=0.312820, depth_time=2026-10-31T18:15:07+00:00, book20_bid_proxy_usdt=78663, book20_ask_proxy_usdt=79944, funding_indicative=-0.000551, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=6962868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T18:15:02+00:00, last15m_closed_end=2026-10-31T18:15+00:00, prior8high=0.404400, depth_time=2026-10-31T18:15:10+00:00, book20_bid_proxy_usdt=2444747, book20_ask_proxy_usdt=2733116, funding_indicative=0.000000, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=38110510. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
