# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T21:00:23Z**
- feed_generated_utc: 2026-11-06T21:00:24+00:00
- source_sha256: `60619f08f4a7b4ec9efebc46b8f5b721b27dac5a9729040629b305fa0df68099`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T21:00+00:00, close=75860, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T21:00+00:00, close=75860, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.138800|-25.37|-47.74|-25.40|30965704|7.21|
|AKE_USDT|0.003717|-22.83|-80.35|-22.86|52232103|5.38|
|JCT_USDT|0.003205|-9.38|-44.11|-9.41|5233316|3.12|
|ANTHROPIC_USDT|1336.770000|-8.03|-20.26|-8.06|5695521|3.37|
|LIT_USDT|3.329100|-1.71|17.87|-1.74|10510865|0.30|
|XPL_USDT|0.057080|-1.43|-26.65|-1.46|5559649|1.75|
|XRP_USDT|1.172000|-1.18|-6.57|-1.21|366728052|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003717|0.003497|0.003717|0.19|N|Y/Y|Y/N|Y|N|
|ANTHROPIC_USDT|1336.770000|1316.030000|1336.770000|2.67|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.003205|0.003191|0.003205|0.39|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.329100|3.268700|3.329100|0.47|N|Y/Y|Y/N|Y|N|
|UAI_USDT|0.138800|0.105200|0.138900|1.56|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.057080|0.056730|0.057080|0.26|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.172000|1.174000|1.172000|1.96|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T21:00:00+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=0.004001, depth_time=2026-11-06T21:00:09+00:00, book20_bid_proxy_usdt=30158, book20_ask_proxy_usdt=29825, funding_indicative=-0.000806, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-22.83%, turnover=52232103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-06T21:00:00+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=1358.890000, depth_time=2026-11-06T21:00:14+00:00, book20_bid_proxy_usdt=21303, book20_ask_proxy_usdt=32303, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.03%, turnover=5695521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-06T21:00:00+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=0.003375, depth_time=2026-11-06T21:00:10+00:00, book20_bid_proxy_usdt=92706, book20_ask_proxy_usdt=77714, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.38%, turnover=5233316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T21:00:01+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=3.343600, depth_time=2026-11-06T21:00:16+00:00, book20_bid_proxy_usdt=25588, book20_ask_proxy_usdt=19690, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=10510865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T21:00:00+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=0.156800, depth_time=2026-11-06T21:00:07+00:00, book20_bid_proxy_usdt=157438, book20_ask_proxy_usdt=136578, funding_indicative=-0.000022, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-25.37%, turnover=30965704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T21:00:01+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=0.057560, depth_time=2026-11-06T21:00:18+00:00, book20_bid_proxy_usdt=515774, book20_ask_proxy_usdt=436812, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=5559649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T21:00:00+00:00, last15m_closed_end=2026-11-06T21:00+00:00, prior8high=1.187700, depth_time=2026-11-06T21:00:22+00:00, book20_bid_proxy_usdt=2405140, book20_ask_proxy_usdt=3694512, funding_indicative=0.000043, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=366728052. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
