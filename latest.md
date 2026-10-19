# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T12:00:26Z**
- feed_generated_utc: 2026-10-19T12:00:28+00:00
- source_sha256: `23391d2c8407de4c44522c401c0850c15ba95715645162548e473285d06c0083`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.992700|-13.56|18.45|-14.98|20615665|0.50|
|HBAR_USDT|0.082920|-5.01|-11.58|-6.43|40428626|1.21|
|STRK_USDT|0.058060|-4.53|-51.32|-5.95|17700423|1.73|
|SAND_USDT|0.058070|-3.58|-12.59|-5.00|14698156|1.73|
|TIA_USDT|0.608100|-1.58|3.29|-3.00|48988831|1.65|
|SEI_USDT|0.059530|-1.17|-16.02|-2.59|8990944|1.68|
|XAU_USDT|4167.850000|0.11|-0.86|-1.31|248118114|0.02|
|XAUT_USDT|4156.160000|0.20|-0.79|-1.22|91349483|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.992700|2.016600|2.009500|1.68|Y|Y/Y|Y/Y|N|Y|
|HBAR_USDT|0.082920|0.082730|0.082930|0.70|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.058070|0.057570|0.058070|0.05|N|Y/Y|Y/N|N|N|
|SEI_USDT|0.059530|0.059210|0.059550|2.17|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058060|0.057600|0.058060|1.92|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.608100|0.602400|0.608100|0.74|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4156.160000|4157.500000|4157.400000|2.82|Y|Y/Y|Y/N|N|N|
|XAU_USDT|4167.850000|4169.160000|4168.360000|1.25|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=2.239100, depth_time=2026-10-19T12:00:08+00:00, book20_bid_proxy_usdt=12631, book20_ask_proxy_usdt=12454, funding_indicative=-0.000645, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.56%, turnover=20615665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=0.084580, depth_time=2026-10-19T12:00:11+00:00, book20_bid_proxy_usdt=448693, book20_ask_proxy_usdt=977522, funding_indicative=-0.000004, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.01%, turnover=40428626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=0.058570, depth_time=2026-10-19T12:00:15+00:00, book20_bid_proxy_usdt=807598, book20_ask_proxy_usdt=798280, funding_indicative=-0.002406, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=14698156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=0.060710, depth_time=2026-10-19T12:00:21+00:00, book20_bid_proxy_usdt=172522, book20_ask_proxy_usdt=245014, funding_indicative=0.000029, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=8990944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=0.060310, depth_time=2026-10-19T12:00:13+00:00, book20_bid_proxy_usdt=646606, book20_ask_proxy_usdt=524141, funding_indicative=0.000050, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=17700423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=0.614900, depth_time=2026-10-19T12:00:17+00:00, book20_bid_proxy_usdt=312168, book20_ask_proxy_usdt=161633, funding_indicative=0.000004, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=48988831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=4169.510000, depth_time=2026-10-19T12:00:24+00:00, book20_bid_proxy_usdt=165342, book20_ask_proxy_usdt=230864, funding_indicative=-0.000014, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.20%, turnover=91349483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-19T12:00:02+00:00, last15m_closed_end=2026-10-19T12:00+00:00, prior8high=4183.360000, depth_time=2026-10-19T12:00:23+00:00, book20_bid_proxy_usdt=558492, book20_ask_proxy_usdt=1338420, funding_indicative=0.000003, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.11%, turnover=248118114. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
