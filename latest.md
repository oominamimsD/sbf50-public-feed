# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T12:45:28Z**
- feed_generated_utc: 2026-10-25T12:45:32+00:00
- source_sha256: `42d8288d6b0af27e14c43eae19f0a50a5e1ec824ccb75e91790e3de90b8e16d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T12:45+00:00, close=80379.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.045900|-31.89|48.30|-32.67|8166241|4.37|
|IRYS_USDT|0.033370|-27.53|161.52|-28.31|27279906|2.99|
|BTW_USDT|1.682300|-3.38|-25.87|-4.16|12652694|0.59|
|STRK_USDT|0.045560|-2.50|-31.12|-3.28|10389993|2.19|
|DOT_USDT|1.025000|-1.35|-8.26|-2.13|12752934|0.98|
|PENGU_USDT|0.007353|-1.20|-1.34|-1.98|5974465|1.36|
|APT_USDT|0.693600|-1.18|-13.02|-1.96|6197438|1.44|
|SUI_USDT|0.916600|-0.90|-6.64|-1.68|70608045|2.18|
|SEI_USDT|0.052480|-0.75|-15.36|-1.53|7775914|1.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.693600|0.689400|0.693600|0.35|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.682300|1.638700|1.682300|2.11|N|N/Y|Y/Y|Y|N|
|DOT_USDT|1.025000|1.013200|1.025000|1.02|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033370|0.033520|0.033370|0.91|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.045900|0.045690|0.045910|0.88|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007353|0.007333|0.007353|0.98|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052480|0.052220|0.052480|5.45|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045560|0.044870|0.045560|0.54|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.916600|0.907500|0.916500|0.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.698900, depth_time=2026-10-25T12:45:22+00:00, book20_bid_proxy_usdt=205622, book20_ask_proxy_usdt=154020, funding_indicative=-0.000127, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=6197438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=1.699100, depth_time=2026-10-25T12:45:12+00:00, book20_bid_proxy_usdt=7065, book20_ask_proxy_usdt=9431, funding_indicative=-0.013403, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=12652694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=1.028700, depth_time=2026-10-25T12:45:18+00:00, book20_bid_proxy_usdt=281805, book20_ask_proxy_usdt=301796, funding_indicative=-0.000046, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=12752934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.036110, depth_time=2026-10-25T12:45:11+00:00, book20_bid_proxy_usdt=179224, book20_ask_proxy_usdt=71718, funding_indicative=0.000012, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-27.53%, turnover=27279906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.050330, depth_time=2026-10-25T12:45:08+00:00, book20_bid_proxy_usdt=104614, book20_ask_proxy_usdt=89437, funding_indicative=-0.001056, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-31.89%, turnover=8166241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.007422, depth_time=2026-10-25T12:45:20+00:00, book20_bid_proxy_usdt=202934, book20_ask_proxy_usdt=222761, funding_indicative=-0.000064, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=5974465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.052880, depth_time=2026-10-25T12:45:28+00:00, book20_bid_proxy_usdt=228607, book20_ask_proxy_usdt=341846, funding_indicative=-0.000084, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=7775914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.046180, depth_time=2026-10-25T12:45:16+00:00, book20_bid_proxy_usdt=1094878, book20_ask_proxy_usdt=893512, funding_indicative=0.000004, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=10389993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T12:45:01+00:00, last15m_closed_end=2026-10-25T12:45+00:00, prior8high=0.920400, depth_time=2026-10-25T12:45:25+00:00, book20_bid_proxy_usdt=1297219, book20_ask_proxy_usdt=939755, funding_indicative=-0.000052, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=70608045. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
