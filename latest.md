# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T07:00:23Z**
- feed_generated_utc: 2026-10-23T07:00:25+00:00
- source_sha256: `3ad3f504dbbd2ca2c94a6006c45194243e7c736ece6d9a23c43055cd87371c9e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T07:00+00:00, close=81851.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T07:00+00:00, close=81851.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.423700|-5.95|10.74|-6.19|9852152|0.29|
|STRK_USDT|0.052780|-2.90|-45.22|-3.14|10391893|1.90|
|XMR_USDT|606.990000|-2.18|11.58|-2.42|21079403|0.17|
|SILVER_USDT|54.120000|-2.06|-5.28|-2.30|334938170|1.85|
|TIA_USDT|0.561600|-1.19|-6.78|-1.43|23639670|1.78|
|XAU_USDT|4021.600000|-1.12|-3.23|-1.36|655187942|0.03|
|XAUT_USDT|4017.140000|-1.10|-3.08|-1.34|260565794|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.423700|3.409600|3.423700|0.23|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.120000|53.720000|54.130000|0.75|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052780|0.052400|0.052800|0.91|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.561600|0.556900|0.562000|1.05|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4017.140000|4008.190000|4017.140000|0.80|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4021.600000|4010.840000|4021.600000|0.44|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|606.990000|607.620000|606.990000|1.15|N|Y/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T07:00:02+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=3.474800, depth_time=2026-10-23T07:00:09+00:00, book20_bid_proxy_usdt=24641, book20_ask_proxy_usdt=24815, funding_indicative=0.000000, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.95%, turnover=9852152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T07:00:01+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=54.680000, depth_time=2026-10-23T07:00:16+00:00, book20_bid_proxy_usdt=32349444, book20_ask_proxy_usdt=31446240, funding_indicative=0.000131, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=334938170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T07:00:02+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=0.053240, depth_time=2026-10-23T07:00:11+00:00, book20_bid_proxy_usdt=548261, book20_ask_proxy_usdt=685555, funding_indicative=-0.000026, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=10391893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T07:00:01+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=0.561700, depth_time=2026-10-23T07:00:17+00:00, book20_bid_proxy_usdt=368234, book20_ask_proxy_usdt=250925, funding_indicative=-0.000044, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=23639670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T07:00:01+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=4032.400000, depth_time=2026-10-23T07:00:23+00:00, book20_bid_proxy_usdt=237422, book20_ask_proxy_usdt=251712, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=260565794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T07:00:01+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=4036.730000, depth_time=2026-10-23T07:00:20+00:00, book20_bid_proxy_usdt=3912808, book20_ask_proxy_usdt=2575567, funding_indicative=0.000096, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=655187942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T07:00:01+00:00, last15m_closed_end=2026-10-23T07:00+00:00, prior8high=616.370000, depth_time=2026-10-23T07:00:10+00:00, book20_bid_proxy_usdt=26101, book20_ask_proxy_usdt=14769, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=21079403. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
