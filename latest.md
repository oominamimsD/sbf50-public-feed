# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T00:30:30Z**
- feed_generated_utc: 2026-10-23T00:30:32+00:00
- source_sha256: `50f6cc693aa7339d9a0893e0bfa860ab32a454620f38902d0afe0e34f81800f6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T00:30+00:00, close=81181.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.373800|-6.65|9.13|-6.08|13405532|0.30|
|STRK_USDT|0.052770|-2.92|-45.23|-2.35|12889923|1.90|
|XMR_USDT|596.030000|-2.75|9.57|-2.18|27206775|0.17|
|PUMPFUN_USDT|0.004571|-2.30|0.99|-1.73|37228501|2.19|
|XPL_USDT|0.075710|-2.30|-10.65|-1.73|5708523|1.32|
|APT_USDT|0.756200|-2.07|-8.52|-1.50|9020668|1.32|
|ARB_USDT|0.179900|-2.03|-5.28|-1.46|32301856|0.56|
|QNT_USDT|187.070000|-1.90|-10.02|-1.33|58454527|0.54|
|TIA_USDT|0.558100|-1.81|-7.36|-1.24|23407744|1.79|
|SEI_USDT|0.057100|-1.67|-7.09|-1.10|9937465|3.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.756200|0.748700|0.756200|1.41|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.179900|0.177500|0.179900|0.27|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.373800|3.363100|3.373800|0.38|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.004571|0.004525|0.004571|1.98|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.070000|185.530000|187.070000|0.44|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057100|0.056780|0.057100|0.24|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052770|0.052550|0.052770|0.30|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.558100|0.555400|0.558100|0.40|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|596.030000|591.180000|596.030000|1.30|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.075710|0.075130|0.075710|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.759400, depth_time=2026-10-23T00:30:19+00:00, book20_bid_proxy_usdt=168807, book20_ask_proxy_usdt=200756, funding_indicative=-0.000048, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=9020668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.180710, depth_time=2026-10-23T00:30:22+00:00, book20_bid_proxy_usdt=109428, book20_ask_proxy_usdt=82557, funding_indicative=-0.000120, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=32301856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=3.464500, depth_time=2026-10-23T00:30:06+00:00, book20_bid_proxy_usdt=23432, book20_ask_proxy_usdt=23131, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.65%, turnover=13405532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.004622, depth_time=2026-10-23T00:30:14+00:00, book20_bid_proxy_usdt=1156193, book20_ask_proxy_usdt=2537714, funding_indicative=0.000025, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=37228501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=188.910000, depth_time=2026-10-23T00:30:24+00:00, book20_bid_proxy_usdt=67464, book20_ask_proxy_usdt=119657, funding_indicative=-0.000141, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=58454527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.057390, depth_time=2026-10-23T00:30:29+00:00, book20_bid_proxy_usdt=486167, book20_ask_proxy_usdt=322400, funding_indicative=-0.000017, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=9937465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.053350, depth_time=2026-10-23T00:30:09+00:00, book20_bid_proxy_usdt=665740, book20_ask_proxy_usdt=493074, funding_indicative=0.000037, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=12889923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.562600, depth_time=2026-10-23T00:30:25+00:00, book20_bid_proxy_usdt=364368, book20_ask_proxy_usdt=410633, funding_indicative=-0.000010, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=23407744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=602.780000, depth_time=2026-10-23T00:30:11+00:00, book20_bid_proxy_usdt=11622, book20_ask_proxy_usdt=15564, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=27206775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T00:30:01+00:00, last15m_closed_end=2026-10-23T00:30+00:00, prior8high=0.076120, depth_time=2026-10-23T00:30:17+00:00, book20_bid_proxy_usdt=478288, book20_ask_proxy_usdt=653389, funding_indicative=-0.000018, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=5708523. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
