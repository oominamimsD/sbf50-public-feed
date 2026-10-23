# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T11:30:33Z**
- feed_generated_utc: 2026-10-23T11:30:35+00:00
- source_sha256: `024d28c7b28aaed1efe78d569d6fb4edd72be606285caae0ac0a848bb7d41b52`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T11:30+00:00, close=81641.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T11:00+00:00, close=81656.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.446270|-11.10|88.73|-11.10|6911384|6.96|
|JCT_USDT|0.004178|-9.33|110.47|-9.33|7742078|7.19|
|LIT_USDT|3.372700|-6.68|9.09|-6.68|9008573|0.30|
|STRK_USDT|0.051680|-4.93|-46.36|-4.93|12112056|1.93|
|QNT_USDT|181.700000|-4.72|-12.60|-4.72|52602173|1.10|
|TIA_USDT|0.547500|-3.67|-9.12|-3.67|25126662|3.65|
|SILVER_USDT|54.100000|-2.09|-5.32|-2.09|331875026|1.85|
|ARB_USDT|0.179960|-2.00|-5.25|-2.00|25023384|0.56|
|PUMPFUN_USDT|0.004592|-1.85|1.45|-1.85|38508422|4.36|
|OP_USDT|0.117850|-1.66|-15.13|-1.66|6084201|1.70|
|ZEC_USDT|1214.690000|-1.58|2.96|-1.58|1903240672|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.179960|0.179250|0.179960|1.11|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004178|0.004042|0.004178|1.09|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.372700|3.349800|3.372700|0.31|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.446270|0.431000|0.447870|3.66|N|Y/Y|N/N|Y|N|
|OP_USDT|0.117850|0.116880|0.117720|2.32|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004592|0.004525|0.004589|13.02|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.700000|181.170000|181.570000|1.20|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.100000|53.870000|54.110000|0.42|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051680|0.051150|0.051680|0.29|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.547500|0.546200|0.547500|0.38|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1214.690000|1198.860000|1214.540000|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.182070, depth_time=2026-10-23T11:30:24+00:00, book20_bid_proxy_usdt=62362, book20_ask_proxy_usdt=62255, funding_indicative=-0.000009, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=25023384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.004210, depth_time=2026-10-23T11:30:08+00:00, book20_bid_proxy_usdt=55113, book20_ask_proxy_usdt=65346, funding_indicative=0.000081, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.33%, turnover=7742078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T11:30:02+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=3.404000, depth_time=2026-10-23T11:30:11+00:00, book20_bid_proxy_usdt=30441, book20_ask_proxy_usdt=27793, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.68%, turnover=9008573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.512000, depth_time=2026-10-23T11:30:07+00:00, book20_bid_proxy_usdt=2748, book20_ask_proxy_usdt=3687, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.10%, turnover=6911384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.118850, depth_time=2026-10-23T11:30:29+00:00, book20_bid_proxy_usdt=105134, book20_ask_proxy_usdt=125967, funding_indicative=0.000046, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=6084201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.004636, depth_time=2026-10-23T11:30:27+00:00, book20_bid_proxy_usdt=1383715, book20_ask_proxy_usdt=2069192, funding_indicative=0.000011, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=38508422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=186.970000, depth_time=2026-10-23T11:30:16+00:00, book20_bid_proxy_usdt=78254, book20_ask_proxy_usdt=85012, funding_indicative=-0.000166, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.72%, turnover=52602173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=54.210000, depth_time=2026-10-23T11:30:22+00:00, book20_bid_proxy_usdt=42422082, book20_ask_proxy_usdt=38433228, funding_indicative=0.000008, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=331875026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.052320, depth_time=2026-10-23T11:30:14+00:00, book20_bid_proxy_usdt=715357, book20_ask_proxy_usdt=703916, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=12112056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=0.553000, depth_time=2026-10-23T11:30:19+00:00, book20_bid_proxy_usdt=399282, book20_ask_proxy_usdt=401661, funding_indicative=0.000024, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.67%, turnover=25126662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T11:30:01+00:00, last15m_closed_end=2026-10-23T11:30+00:00, prior8high=1230.570000, depth_time=2026-10-23T11:30:32+00:00, book20_bid_proxy_usdt=750509, book20_ask_proxy_usdt=182948, funding_indicative=0.000032, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=1903240672. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
