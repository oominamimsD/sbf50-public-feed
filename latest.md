# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T13:00:36Z**
- feed_generated_utc: 2026-10-23T13:00:39+00:00
- source_sha256: `0f09608a7a33798944414643b89b62534da3366d00eb41a8a1caaaa42e4f0555`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T13:00+00:00, close=81711.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T13:00+00:00, close=81711.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.433650|-13.62|83.40|-13.69|6620350|1.15|
|JCT_USDT|0.004126|-10.46|107.85|-10.53|6458825|7.27|
|LIT_USDT|3.380600|-6.46|9.35|-6.53|8837496|0.30|
|QNT_USDT|182.430000|-4.34|-12.25|-4.41|55925218|0.55|
|TIA_USDT|0.548700|-3.46|-8.92|-3.53|25463000|3.65|
|STRK_USDT|0.052950|-2.59|-45.04|-2.66|12450661|1.89|
|SILVER_USDT|53.910000|-2.44|-5.65|-2.51|332379917|1.85|
|ARB_USDT|0.180410|-1.75|-5.01|-1.82|25518259|0.55|
|PUMPFUN_USDT|0.004600|-1.68|1.63|-1.75|40489940|2.17|
|OP_USDT|0.118020|-1.52|-15.01|-1.59|6245076|0.85|
|XMR_USDT|606.860000|-0.98|11.56|-1.05|15349495|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180410|0.179250|0.180410|2.05|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004126|0.004085|0.004126|0.96|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.380600|3.341700|3.380600|0.75|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.433650|0.426720|0.433650|0.41|N|Y/Y|N/N|Y|N|
|OP_USDT|0.118020|0.116880|0.118020|0.15|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004600|0.004525|0.004600|0.27|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.430000|180.980000|182.430000|0.88|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.910000|53.860000|53.910000|3.19|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052950|0.051150|0.052950|0.93|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.548700|0.544800|0.548800|0.26|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|606.860000|605.750000|606.860000|0.45|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.181300, depth_time=2026-10-23T13:00:28+00:00, book20_bid_proxy_usdt=106148, book20_ask_proxy_usdt=71838, funding_indicative=0.000005, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=25518259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.004254, depth_time=2026-10-23T13:00:12+00:00, book20_bid_proxy_usdt=71584, book20_ask_proxy_usdt=58756, funding_indicative=0.000065, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=6458825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=3.406000, depth_time=2026-10-23T13:00:14+00:00, book20_bid_proxy_usdt=21951, book20_ask_proxy_usdt=24065, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.46%, turnover=8837496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.496320, depth_time=2026-10-23T13:00:09+00:00, book20_bid_proxy_usdt=3601, book20_ask_proxy_usdt=6200, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.62%, turnover=6620350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.118580, depth_time=2026-10-23T13:00:33+00:00, book20_bid_proxy_usdt=146657, book20_ask_proxy_usdt=103916, funding_indicative=0.000007, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=6245076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.004674, depth_time=2026-10-23T13:00:30+00:00, book20_bid_proxy_usdt=2129371, book20_ask_proxy_usdt=1507344, funding_indicative=0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=40489940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=183.550000, depth_time=2026-10-23T13:00:17+00:00, book20_bid_proxy_usdt=92775, book20_ask_proxy_usdt=62612, funding_indicative=-0.000181, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=55925218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=54.210000, depth_time=2026-10-23T13:00:25+00:00, book20_bid_proxy_usdt=37496290, book20_ask_proxy_usdt=34175718, funding_indicative=0.000046, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=332379917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.053770, depth_time=2026-10-23T13:00:23+00:00, book20_bid_proxy_usdt=947858, book20_ask_proxy_usdt=682469, funding_indicative=0.000004, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=12450661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=0.550500, depth_time=2026-10-23T13:00:19+00:00, book20_bid_proxy_usdt=302230, book20_ask_proxy_usdt=362872, funding_indicative=0.000019, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=25463000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T12:59:59+00:00, last15m_closed_end=2026-10-23T13:00+00:00, prior8high=612.540000, depth_time=2026-10-23T13:00:35+00:00, book20_bid_proxy_usdt=17692, book20_ask_proxy_usdt=23788, funding_indicative=0.000100, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=15349495. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
