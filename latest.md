# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T20:00:25Z**
- feed_generated_utc: 2026-10-17T20:00:27+00:00
- source_sha256: `47dca998a2c7cf24a2bf21049d887a9af5d994456446d56736e69465dff2fbe1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.255700|-7.28|UNKNOWN|-7.59|6687076|7.83|
|STRK_USDT|0.065270|-4.18|-30.14|-4.49|15103097|1.53|
|QNT_USDT|198.910000|-1.82|-18.85|-2.13|59862453|0.50|
|EIGEN_USDT|0.255400|-1.65|8.40|-1.96|9612397|3.92|
|ARB_USDT|0.183360|-1.40|-1.77|-1.71|27480098|0.55|
|AAVE_USDT|152.690000|-1.24|-10.91|-1.55|17602460|0.66|
|PUMPFUN_USDT|0.004466|-1.17|-21.99|-1.48|39800347|2.24|
|ENA_USDT|0.191740|-0.71|-13.64|-1.02|27026816|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|152.690000|151.380000|152.690000|0.43|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.183360|0.180610|0.183360|10.82|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.255700|0.249000|0.255700|0.45|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.255400|0.247500|0.255400|0.18|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.191740|0.187050|0.191740|0.52|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004466|0.004374|0.004466|0.57|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.910000|196.660000|198.880000|0.58|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.065270|0.064620|0.065270|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=152.960000, depth_time=2026-10-17T20:00:19+00:00, book20_bid_proxy_usdt=390126, book20_ask_proxy_usdt=365360, funding_indicative=0.000100, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=17602460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=0.183740, depth_time=2026-10-17T20:00:16+00:00, book20_bid_proxy_usdt=64391, book20_ask_proxy_usdt=91366, funding_indicative=0.000006, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=27480098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=0.265500, depth_time=2026-10-17T20:00:07+00:00, book20_bid_proxy_usdt=67755, book20_ask_proxy_usdt=67702, funding_indicative=-0.001262, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.28%, turnover=6687076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=0.255800, depth_time=2026-10-17T20:00:14+00:00, book20_bid_proxy_usdt=596350, book20_ask_proxy_usdt=540540, funding_indicative=-0.000021, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=9612397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=0.192000, depth_time=2026-10-17T20:00:23+00:00, book20_bid_proxy_usdt=216740, book20_ask_proxy_usdt=254138, funding_indicative=0.000024, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.71%, turnover=27026816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=0.004486, depth_time=2026-10-17T20:00:22+00:00, book20_bid_proxy_usdt=1584028, book20_ask_proxy_usdt=1134387, funding_indicative=-0.000005, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=39800347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=200.890000, depth_time=2026-10-17T20:00:12+00:00, book20_bid_proxy_usdt=53574, book20_ask_proxy_usdt=54610, funding_indicative=-0.000042, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=59862453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T20:00:00+00:00, last15m_closed_end=2026-10-17T20:00+00:00, prior8high=0.068240, depth_time=2026-10-17T20:00:10+00:00, book20_bid_proxy_usdt=153872, book20_ask_proxy_usdt=267628, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.18%, turnover=15103097. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
