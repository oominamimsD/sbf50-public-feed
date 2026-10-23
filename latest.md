# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T07:45:20Z**
- feed_generated_utc: 2026-10-23T07:45:22+00:00
- source_sha256: `6a81b0c6b46f530bab6814c7c7894084b25d2ad7c2ebfa6b95f9d784ce9f662d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T07:45+00:00, close=81660.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T07:00+00:00, close=81851.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004197|-8.91|111.43|-8.92|8297970|7.15|
|LIT_USDT|3.437300|-4.89|11.18|-4.90|9983633|0.29|
|SILVER_USDT|54.100000|-2.09|-5.32|-2.10|342789888|1.85|
|STRK_USDT|0.053400|-1.76|-44.58|-1.77|10496191|1.87|
|TIA_USDT|0.560000|-1.47|-7.05|-1.48|24481002|3.57|
|PUMPFUN_USDT|0.004611|-1.45|1.87|-1.46|37688877|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004197|0.004179|0.004197|1.11|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.437300|3.409600|3.441600|1.19|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004611|0.004611|0.004611|0.61|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.100000|53.920000|54.100000|0.70|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053400|0.052400|0.053400|0.24|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.560000|0.556900|0.560000|2.41|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T07:45:01+00:00, last15m_closed_end=2026-10-23T07:45+00:00, prior8high=0.004429, depth_time=2026-10-23T07:45:07+00:00, book20_bid_proxy_usdt=39638, book20_ask_proxy_usdt=33137, funding_indicative=0.000065, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.91%, turnover=8297970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T07:45:01+00:00, last15m_closed_end=2026-10-23T07:45+00:00, prior8high=3.454700, depth_time=2026-10-23T07:45:09+00:00, book20_bid_proxy_usdt=26214, book20_ask_proxy_usdt=21582, funding_indicative=0.000024, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=9983633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T07:45:01+00:00, last15m_closed_end=2026-10-23T07:45+00:00, prior8high=0.004684, depth_time=2026-10-23T07:45:19+00:00, book20_bid_proxy_usdt=1722028, book20_ask_proxy_usdt=1744320, funding_indicative=0.000006, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=37688877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T07:45:01+00:00, last15m_closed_end=2026-10-23T07:45+00:00, prior8high=54.680000, depth_time=2026-10-23T07:45:10+00:00, book20_bid_proxy_usdt=37621569, book20_ask_proxy_usdt=31191173, funding_indicative=0.000164, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=342789888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T07:45:01+00:00, last15m_closed_end=2026-10-23T07:45+00:00, prior8high=0.053510, depth_time=2026-10-23T07:45:14+00:00, book20_bid_proxy_usdt=506266, book20_ask_proxy_usdt=621193, funding_indicative=-0.000027, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=10496191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T07:45:01+00:00, last15m_closed_end=2026-10-23T07:45+00:00, prior8high=0.562000, depth_time=2026-10-23T07:45:17+00:00, book20_bid_proxy_usdt=380534, book20_ask_proxy_usdt=239926, funding_indicative=-0.000019, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=24481002. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
