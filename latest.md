# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T03:15:18Z**
- feed_generated_utc: 2026-11-11T03:15:19+00:00
- source_sha256: `d7484e8c797f82f3153437415533c2341749aec200bad65acf29197a49ce514e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T03:15+00:00, close=73795.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T03:00+00:00, close=73615.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002615|-10.26|-37.07|-11.10|10379146|3.82|
|PIEVERSE_USDT|1.835300|-9.41|56.14|-10.25|5050015|2.73|
|ZEC_USDT|1033.650000|-5.46|-14.13|-6.30|2170990657|0.10|
|DASH_USDT|44.080000|-2.34|-4.46|-3.18|14268374|4.54|
|UNI_USDT|6.740000|-1.31|-8.33|-2.15|34829294|1.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002615|0.002762|0.002615|4.37|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|44.080000|42.750000|44.080000|4.95|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.835300|1.682600|1.835300|3.16|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.740000|6.626000|6.739000|1.00|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1033.650000|1007.730000|1033.940000|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T03:15:01+00:00, last15m_closed_end=2026-11-11T03:15+00:00, prior8high=0.003032, depth_time=2026-11-11T03:15:07+00:00, book20_bid_proxy_usdt=41682, book20_ask_proxy_usdt=39702, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.26%, turnover=10379146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T03:15:01+00:00, last15m_closed_end=2026-11-11T03:15+00:00, prior8high=44.600000, depth_time=2026-11-11T03:15:12+00:00, book20_bid_proxy_usdt=322375, book20_ask_proxy_usdt=589568, funding_indicative=-0.000111, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=14268374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T03:15:01+00:00, last15m_closed_end=2026-11-11T03:15+00:00, prior8high=1.853200, depth_time=2026-11-11T03:15:10+00:00, book20_bid_proxy_usdt=17639, book20_ask_proxy_usdt=11963, funding_indicative=0.000150, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.41%, turnover=5050015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T03:15:01+00:00, last15m_closed_end=2026-11-11T03:15+00:00, prior8high=6.820000, depth_time=2026-11-11T03:15:15+00:00, book20_bid_proxy_usdt=2997133, book20_ask_proxy_usdt=3032108, funding_indicative=0.000021, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=34829294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T03:15:01+00:00, last15m_closed_end=2026-11-11T03:15+00:00, prior8high=1042.760000, depth_time=2026-11-11T03:15:12+00:00, book20_bid_proxy_usdt=255724, book20_ask_proxy_usdt=181063, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.46%, turnover=2170990657. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
