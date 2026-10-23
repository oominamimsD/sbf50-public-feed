# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T13:15:35Z**
- feed_generated_utc: 2026-10-23T13:15:38+00:00
- source_sha256: `5fadb714b06353e27462bc0b61ff54c2aba796ab86f138fd7e67ae0c8710b4da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T13:15+00:00, close=81618.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T13:00+00:00, close=81711.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.436860|-12.98|84.75|-12.95|6295332|3.21|
|JCT_USDT|0.004128|-10.41|107.95|-10.38|5615694|7.26|
|LIT_USDT|3.353200|-7.22|8.46|-7.19|8501474|0.30|
|QNT_USDT|181.780000|-4.68|-12.56|-4.65|55131211|0.55|
|TIA_USDT|0.544900|-4.13|-9.56|-4.10|24364539|3.67|
|STRK_USDT|0.052550|-3.32|-45.46|-3.29|11920148|1.90|
|SILVER_USDT|54.000000|-2.28|-5.49|-2.25|321715154|1.85|
|ARB_USDT|0.179480|-2.26|-5.50|-2.23|23860221|0.56|
|PUMPFUN_USDT|0.004576|-2.20|1.10|-2.17|39261377|2.19|
|OP_USDT|0.117660|-1.82|-15.27|-1.79|6075121|0.85|
|APT_USDT|0.762500|-1.25|-7.76|-1.22|7447121|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.762500|0.762800|0.762500|1.82|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.179480|0.179250|0.179480|1.13|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004128|0.004085|0.004128|0.73|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.353200|3.341700|3.353200|0.96|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.436860|0.426720|0.436860|0.72|N|Y/Y|N/N|Y|N|
|OP_USDT|0.117660|0.116880|0.117640|0.72|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004576|0.004525|0.004576|2.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.780000|180.980000|181.790000|1.38|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.000000|53.830000|54.000000|2.93|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052550|0.051150|0.052530|0.44|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.544900|0.544800|0.544900|2.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.770000, depth_time=2026-10-23T13:15:33+00:00, book20_bid_proxy_usdt=131462, book20_ask_proxy_usdt=158379, funding_indicative=0.000047, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=7447121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.181300, depth_time=2026-10-23T13:15:26+00:00, book20_bid_proxy_usdt=114216, book20_ask_proxy_usdt=61477, funding_indicative=0.000001, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=23860221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.004254, depth_time=2026-10-23T13:15:10+00:00, book20_bid_proxy_usdt=51945, book20_ask_proxy_usdt=45141, funding_indicative=0.000092, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.41%, turnover=5615694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=3.406000, depth_time=2026-10-23T13:15:13+00:00, book20_bid_proxy_usdt=29595, book20_ask_proxy_usdt=19383, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.22%, turnover=8501474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.496320, depth_time=2026-10-23T13:15:08+00:00, book20_bid_proxy_usdt=3423, book20_ask_proxy_usdt=3853, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.98%, turnover=6295332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.118580, depth_time=2026-10-23T13:15:30+00:00, book20_bid_proxy_usdt=173969, book20_ask_proxy_usdt=106433, funding_indicative=0.000004, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=6075121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.004674, depth_time=2026-10-23T13:15:29+00:00, book20_bid_proxy_usdt=2040342, book20_ask_proxy_usdt=1228114, funding_indicative=0.000021, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=39261377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=183.550000, depth_time=2026-10-23T13:15:16+00:00, book20_bid_proxy_usdt=83138, book20_ask_proxy_usdt=95055, funding_indicative=-0.000195, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.68%, turnover=55131211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=54.210000, depth_time=2026-10-23T13:15:24+00:00, book20_bid_proxy_usdt=28856782, book20_ask_proxy_usdt=30575059, funding_indicative=0.000059, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=321715154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.053770, depth_time=2026-10-23T13:15:21+00:00, book20_bid_proxy_usdt=772670, book20_ask_proxy_usdt=522735, funding_indicative=-0.000009, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.32%, turnover=11920148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T13:14:59+00:00, last15m_closed_end=2026-10-23T13:15+00:00, prior8high=0.550500, depth_time=2026-10-23T13:15:18+00:00, book20_bid_proxy_usdt=229244, book20_ask_proxy_usdt=327397, funding_indicative=0.000000, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.13%, turnover=24364539. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
