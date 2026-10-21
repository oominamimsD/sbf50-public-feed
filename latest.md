# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T16:15:17Z**
- feed_generated_utc: 2026-10-21T16:15:19+00:00
- source_sha256: `52b15785c3f1043940aa42b22769c0c13f95a7c20cb638098ab19aa98c73a192`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T16:15+00:00, close=84555.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002352|-17.29|65.86|-17.35|8893890|8.52|
|BR_USDT|0.526500|-2.78|29.12|-2.84|17221777|0.95|
|BTW_USDT|1.431400|-2.61|-39.82|-2.67|27203759|2.10|
|ICNT_USDT|0.186300|-1.16|70.29|-1.22|5732962|5.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BR_USDT|0.526500|0.532370|0.526500|2.40|Y|Y/Y|Y/Y|N|Y|
|BTW_USDT|1.431400|1.461100|1.431300|3.63|Y|Y/Y|Y/Y|N|Y|
|DOOD_USDT|0.002352|0.002703|0.002374|2.43|Y|Y/N|N/N|N|N|
|ICNT_USDT|0.186300|0.187900|0.186300|0.59|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BR_USDT: quote_utc=2026-10-21T16:15:00+00:00, last15m_closed_end=2026-10-21T16:15+00:00, prior8high=0.617380, depth_time=2026-10-21T16:15:11+00:00, book20_bid_proxy_usdt=4999, book20_ask_proxy_usdt=2179, funding_indicative=-0.000087, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=17221777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T16:15:00+00:00, last15m_closed_end=2026-10-21T16:15+00:00, prior8high=1.627800, depth_time=2026-10-21T16:15:14+00:00, book20_bid_proxy_usdt=5594, book20_ask_proxy_usdt=8476, funding_indicative=-0.003633, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=27203759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T16:15:00+00:00, last15m_closed_end=2026-10-21T16:15+00:00, prior8high=0.004804, depth_time=2026-10-21T16:15:09+00:00, book20_bid_proxy_usdt=147421, book20_ask_proxy_usdt=78173, funding_indicative=-0.012076, next_funding_utc=2026-10-21T17:00:00+00:00, funding_cycle_h=1, 24h_change=-17.29%, turnover=8893890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-21T16:15:00+00:00, last15m_closed_end=2026-10-21T16:15+00:00, prior8high=0.199200, depth_time=2026-10-21T16:15:16+00:00, book20_bid_proxy_usdt=256068, book20_ask_proxy_usdt=113378, funding_indicative=-0.000167, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=5732962. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
