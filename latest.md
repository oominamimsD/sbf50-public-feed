# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T04:30:21Z**
- feed_generated_utc: 2026-11-08T04:30:23+00:00
- source_sha256: `879fe38cadcfcc221f7448a07399eb0098e1faeaa88fff8bda7a7032842b4fd2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T04:30+00:00, close=75914.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.133680|-14.18|-42.41|-14.42|9320052|3.74|
|ONE_USDT|0.001850|-9.16|57.56|-9.40|26507709|0.54|
|ENA_USDT|0.153960|-2.66|-20.64|-2.90|27816915|0.65|
|QNT_USDT|194.620000|-2.12|-3.19|-2.36|45042942|1.54|
|WLD_USDT|0.330700|-1.46|-18.22|-1.70|24380979|3.02|
|TIA_USDT|0.435400|-1.40|-11.16|-1.64|7222352|2.30|
|ONDO_USDT|0.359600|-0.96|-12.80|-1.20|8430545|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.133680|0.117040|0.133710|3.63|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153960|0.153550|0.153960|0.51|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359600|0.358700|0.359600|1.00|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001850|0.001812|0.001850|0.86|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.620000|193.120000|194.620000|0.53|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.435400|0.434500|0.435400|0.25|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330700|0.329000|0.330700|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=0.157480, depth_time=2026-11-08T04:30:06+00:00, book20_bid_proxy_usdt=4866, book20_ask_proxy_usdt=11603, funding_indicative=0.000256, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.18%, turnover=9320052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=0.155790, depth_time=2026-11-08T04:30:08+00:00, book20_bid_proxy_usdt=432070, book20_ask_proxy_usdt=277277, funding_indicative=0.000014, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=27816915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=0.362000, depth_time=2026-11-08T04:30:19+00:00, book20_bid_proxy_usdt=2465572, book20_ask_proxy_usdt=1719016, funding_indicative=-0.000009, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=8430545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=0.002015, depth_time=2026-11-08T04:30:07+00:00, book20_bid_proxy_usdt=9889, book20_ask_proxy_usdt=9360, funding_indicative=0.000037, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.16%, turnover=26507709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=195.100000, depth_time=2026-11-08T04:30:13+00:00, book20_bid_proxy_usdt=86688, book20_ask_proxy_usdt=60661, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=45042942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=0.438500, depth_time=2026-11-08T04:30:18+00:00, book20_bid_proxy_usdt=401852, book20_ask_proxy_usdt=242095, funding_indicative=0.000010, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=7222352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T04:29:59+00:00, last15m_closed_end=2026-11-08T04:30+00:00, prior8high=0.332300, depth_time=2026-11-08T04:30:12+00:00, book20_bid_proxy_usdt=3419331, book20_ask_proxy_usdt=3161653, funding_indicative=-0.000135, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=24380979. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
