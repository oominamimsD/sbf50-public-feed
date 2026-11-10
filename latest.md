# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T03:30:37Z**
- feed_generated_utc: 2026-11-10T03:30:39+00:00
- source_sha256: `5cbd46413c3a39b0d30ad23b6359806f0541825133082d78f851131a35992367`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T03:30+00:00, close=74634.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T03:00+00:00, close=74843.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002662|-45.64|-51.61|-44.50|14914240|3.78|
|JCT_USDT|0.008399|-17.09|94.55|-15.95|27730405|1.19|
|ARB_USDT|0.171770|-6.66|7.80|-5.52|31441309|1.75|
|ZEC_USDT|1147.610000|-6.37|-8.49|-5.23|2408569897|0.26|
|DOT_USDT|0.851000|-4.47|-8.89|-3.33|10753116|1.18|
|DASH_USDT|45.870000|-3.67|-2.81|-2.53|15241443|2.18|
|QNT_USDT|193.070000|-3.48|-4.63|-2.34|37043929|0.52|
|HYPE_USDT|73.784000|-3.31|-13.91|-2.17|46224893|0.14|
|PUMPFUN_USDT|0.003564|-3.20|-13.15|-2.06|7973762|2.81|
|AAVE_USDT|129.180000|-3.12|-1.05|-1.98|13609242|0.77|
|WLD_USDT|0.315900|-3.06|-17.13|-1.92|26257831|3.17|
|SOL_USDT|85.700000|-2.49|-8.35|-1.35|634088350|1.17|
|HBAR_USDT|0.066770|-2.48|-5.25|-1.34|9378934|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.180000|130.130000|129.180000|2.70|Y|Y/Y|N/N|Y|N|
|AKE_USDT|0.002662|0.002302|0.002665|0.61|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171770|0.171980|0.171770|0.86|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.870000|45.960000|45.870000|0.55|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.851000|0.849300|0.851000|0.92|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066770|0.066500|0.066770|0.53|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|73.784000|73.740000|73.784000|2.90|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008399|0.008280|0.008401|1.04|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003564|0.003550|0.003564|0.46|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.070000|192.510000|193.070000|0.18|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.700000|85.840000|85.700000|1.62|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.315900|0.314400|0.315900|0.91|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1147.610000|1141.980000|1147.610000|1.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=132.350000, depth_time=2026-11-10T03:30:27+00:00, book20_bid_proxy_usdt=499220, book20_ask_proxy_usdt=423453, funding_indicative=0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=13609242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.002982, depth_time=2026-11-10T03:30:07+00:00, book20_bid_proxy_usdt=59694, book20_ask_proxy_usdt=18102, funding_indicative=0.000050, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-45.64%, turnover=14914240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.174400, depth_time=2026-11-10T03:30:10+00:00, book20_bid_proxy_usdt=60621, book20_ask_proxy_usdt=61233, funding_indicative=-0.000010, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.66%, turnover=31441309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=47.090000, depth_time=2026-11-10T03:30:20+00:00, book20_bid_proxy_usdt=563052, book20_ask_proxy_usdt=629655, funding_indicative=-0.000021, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=15241443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.858400, depth_time=2026-11-10T03:30:17+00:00, book20_bid_proxy_usdt=715145, book20_ask_proxy_usdt=530190, funding_indicative=-0.000008, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.47%, turnover=10753116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.067110, depth_time=2026-11-10T03:30:36+00:00, book20_bid_proxy_usdt=708419, book20_ask_proxy_usdt=747284, funding_indicative=0.000055, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=9378934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=75.171000, depth_time=2026-11-10T03:30:23+00:00, book20_bid_proxy_usdt=86736, book20_ask_proxy_usdt=89550, funding_indicative=0.000039, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=46224893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.010764, depth_time=2026-11-10T03:30:10+00:00, book20_bid_proxy_usdt=21988, book20_ask_proxy_usdt=14532, funding_indicative=0.000636, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.09%, turnover=27730405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.003614, depth_time=2026-11-10T03:30:25+00:00, book20_bid_proxy_usdt=2365605, book20_ask_proxy_usdt=3198167, funding_indicative=0.000026, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=7973762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=195.060000, depth_time=2026-11-10T03:30:21+00:00, book20_bid_proxy_usdt=63545, book20_ask_proxy_usdt=82736, funding_indicative=0.000035, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=37043929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=86.670000, depth_time=2026-11-10T03:30:34+00:00, book20_bid_proxy_usdt=16764104, book20_ask_proxy_usdt=15425752, funding_indicative=0.000005, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=634088350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=0.318300, depth_time=2026-11-10T03:30:30+00:00, book20_bid_proxy_usdt=5596438, book20_ask_proxy_usdt=5663024, funding_indicative=0.000039, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=26257831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T03:30:00+00:00, last15m_closed_end=2026-11-10T03:30+00:00, prior8high=1178.300000, depth_time=2026-11-10T03:30:13+00:00, book20_bid_proxy_usdt=307494, book20_ask_proxy_usdt=255628, funding_indicative=0.000071, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.37%, turnover=2408569897. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
