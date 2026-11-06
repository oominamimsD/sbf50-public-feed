# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T20:30:20Z**
- feed_generated_utc: 2026-11-06T20:30:21+00:00
- source_sha256: `fe49e1e1c49305bb81e31b6cc1bd1005eb592845bd2424b4fe2020dba0d46aa7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T20:30+00:00, close=75790.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.125700|-33.84|-52.67|-33.79|30235025|7.96|
|ANTHROPIC_USDT|1320.530000|-7.73|-21.22|-7.68|6351799|1.21|
|LIT_USDT|3.308100|-2.48|17.13|-2.43|11050789|0.30|
|PUMPFUN_USDT|0.003956|-2.20|-3.67|-2.15|10804103|5.06|
|NEAR_USDT|3.702000|-1.49|-14.34|-1.44|45344585|2.70|
|UNI_USDT|6.874000|-1.13|-1.05|-1.08|32694775|1.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1320.530000|1316.030000|1320.530000|2.30|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.308100|3.268700|3.308100|0.68|N|Y/Y|Y/N|Y|N|
|NEAR_USDT|3.702000|3.701000|3.702000|0.72|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003956|0.003930|0.003956|0.35|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.125700|0.105200|0.125700|0.69|N|Y/Y|Y/N|Y|N|
|UNI_USDT|6.874000|6.868000|6.874000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T20:30:00+00:00, last15m_closed_end=2026-11-06T20:30+00:00, prior8high=1365.730000, depth_time=2026-11-06T20:30:09+00:00, book20_bid_proxy_usdt=268247, book20_ask_proxy_usdt=46709, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.73%, turnover=6351799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T20:30:00+00:00, last15m_closed_end=2026-11-06T20:30+00:00, prior8high=3.370000, depth_time=2026-11-06T20:30:11+00:00, book20_bid_proxy_usdt=25514, book20_ask_proxy_usdt=23742, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=11050789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-06T20:30:00+00:00, last15m_closed_end=2026-11-06T20:30+00:00, prior8high=3.768000, depth_time=2026-11-06T20:30:16+00:00, book20_bid_proxy_usdt=3745180, book20_ask_proxy_usdt=2774859, funding_indicative=0.000100, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=45344585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T20:30:00+00:00, last15m_closed_end=2026-11-06T20:30+00:00, prior8high=0.004035, depth_time=2026-11-06T20:30:14+00:00, book20_bid_proxy_usdt=1335249, book20_ask_proxy_usdt=1775135, funding_indicative=0.000029, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=10804103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T20:30:00+00:00, last15m_closed_end=2026-11-06T20:30+00:00, prior8high=0.231100, depth_time=2026-11-06T20:30:06+00:00, book20_bid_proxy_usdt=130770, book20_ask_proxy_usdt=125752, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-33.84%, turnover=30235025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-06T20:30:00+00:00, last15m_closed_end=2026-11-06T20:30+00:00, prior8high=6.946000, depth_time=2026-11-06T20:30:19+00:00, book20_bid_proxy_usdt=2174247, book20_ask_proxy_usdt=2891110, funding_indicative=0.000084, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=32694775. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
