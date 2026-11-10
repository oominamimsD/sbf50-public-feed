# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T01:00:18Z**
- feed_generated_utc: 2026-11-10T01:00:19+00:00
- source_sha256: `9ad290d57939b197198185eb8acbef5ad2e4cd23a9ff2f6806c53a4b23a4dad0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T01:00+00:00, close=75052, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T01:00+00:00, close=75052, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002493|-49.09|-54.68|-48.50|12526690|4.00|
|ZEC_USDT|1169.990000|-4.54|-6.70|-3.95|2476598716|0.09|
|DOT_USDT|0.854100|-4.13|-8.56|-3.54|10793552|1.17|
|QNT_USDT|194.180000|-2.92|-4.08|-2.33|41733628|0.52|
|HBAR_USDT|0.066620|-2.70|-5.46|-2.11|8988937|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002493|0.002154|0.002492|7.67|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.854100|0.852500|0.854100|0.11|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066620|0.066320|0.066620|0.22|N|Y/Y|Y/N|Y|N|
|QNT_USDT|194.180000|193.200000|194.180000|1.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1169.990000|1152.430000|1169.990000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T00:59:59+00:00, last15m_closed_end=2026-11-10T01:00+00:00, prior8high=0.005150, depth_time=2026-11-10T01:00:07+00:00, book20_bid_proxy_usdt=30602, book20_ask_proxy_usdt=62832, funding_indicative=-0.000664, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-49.09%, turnover=12526690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T00:59:59+00:00, last15m_closed_end=2026-11-10T01:00+00:00, prior8high=0.863300, depth_time=2026-11-10T01:00:11+00:00, book20_bid_proxy_usdt=517582, book20_ask_proxy_usdt=610530, funding_indicative=0.000058, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=10793552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T00:59:59+00:00, last15m_closed_end=2026-11-10T01:00+00:00, prior8high=0.067330, depth_time=2026-11-10T01:00:17+00:00, book20_bid_proxy_usdt=622150, book20_ask_proxy_usdt=722962, funding_indicative=0.000098, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=8988937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T00:59:59+00:00, last15m_closed_end=2026-11-10T01:00+00:00, prior8high=197.070000, depth_time=2026-11-10T01:00:14+00:00, book20_bid_proxy_usdt=42193, book20_ask_proxy_usdt=87584, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=41733628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T00:59:59+00:00, last15m_closed_end=2026-11-10T01:00+00:00, prior8high=1182.690000, depth_time=2026-11-10T01:00:09+00:00, book20_bid_proxy_usdt=153050, book20_ask_proxy_usdt=1316257, funding_indicative=0.000098, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.54%, turnover=2476598716. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
