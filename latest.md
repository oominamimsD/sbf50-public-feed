# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T08:30:33Z**
- feed_generated_utc: 2026-11-10T08:30:34+00:00
- source_sha256: `6b9613ca7709f5908fcebf6f5d779ca29600ee8b987cc6edca5cda5c2ff08946`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T08:30+00:00, close=74641.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002469|-49.58|-55.12|-48.44|15338105|8.11|
|JCT_USDT|0.006074|-40.04|40.69|-38.90|24832568|3.29|
|ARB_USDT|0.167400|-9.04|5.06|-7.90|36961674|0.60|
|ZEC_USDT|1140.740000|-6.93|-9.03|-5.79|2348385650|0.09|
|AAVE_USDT|125.850000|-5.62|-3.60|-4.48|12764323|0.80|
|QNT_USDT|189.540000|-5.24|-6.37|-4.10|33431558|0.53|
|DOT_USDT|0.855000|-4.02|-8.46|-2.88|8432237|1.17|
|DASH_USDT|45.710000|-4.01|-3.15|-2.87|10904369|2.19|
|PUMPFUN_USDT|0.003540|-3.85|-13.74|-2.71|7349451|2.82|
|SOL_USDT|85.660000|-2.53|-8.39|-1.39|642157027|1.17|
|XRP_USDT|1.089600|-2.18|-12.72|-1.04|269202790|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.850000|125.050000|125.850000|1.00|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002469|0.002459|0.002469|0.74|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167400|0.166370|0.167400|1.11|N|Y/Y|Y/N|Y|N|
|DASH_USDT|45.710000|45.510000|45.700000|1.88|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.855000|0.853600|0.855200|0.59|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006074|0.005560|0.006074|1.38|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003540|0.003555|0.003541|25.79|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|189.540000|189.670000|189.540000|1.57|Y|Y/Y|Y/Y|Y|Y|
|SOL_USDT|85.660000|85.770000|85.660000|1.33|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.089600|1.089900|1.089600|2.13|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1140.740000|1144.770000|1140.740000|1.36|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=127.890000, depth_time=2026-11-10T08:30:17+00:00, book20_bid_proxy_usdt=596512, book20_ask_proxy_usdt=370252, funding_indicative=0.000067, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.62%, turnover=12764323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=0.002556, depth_time=2026-11-10T08:30:08+00:00, book20_bid_proxy_usdt=63415, book20_ask_proxy_usdt=46974, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.58%, turnover=15338105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=0.172460, depth_time=2026-11-10T08:30:12+00:00, book20_bid_proxy_usdt=47675, book20_ask_proxy_usdt=39654, funding_indicative=-0.000102, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.04%, turnover=36961674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=45.950000, depth_time=2026-11-10T08:30:25+00:00, book20_bid_proxy_usdt=327924, book20_ask_proxy_usdt=621008, funding_indicative=0.000030, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=10904369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=0.862700, depth_time=2026-11-10T08:30:21+00:00, book20_bid_proxy_usdt=495519, book20_ask_proxy_usdt=848432, funding_indicative=-0.000054, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=8432237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=0.006949, depth_time=2026-11-10T08:30:10+00:00, book20_bid_proxy_usdt=23445, book20_ask_proxy_usdt=26467, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-40.04%, turnover=24832568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=0.003602, depth_time=2026-11-10T08:30:26+00:00, book20_bid_proxy_usdt=2434562, book20_ask_proxy_usdt=2829509, funding_indicative=0.000038, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=7349451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=192.140000, depth_time=2026-11-10T08:30:20+00:00, book20_bid_proxy_usdt=54902, book20_ask_proxy_usdt=90831, funding_indicative=-0.000157, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=33431558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=86.490000, depth_time=2026-11-10T08:30:29+00:00, book20_bid_proxy_usdt=20022244, book20_ask_proxy_usdt=16715329, funding_indicative=0.000082, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=642157027. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=1.106100, depth_time=2026-11-10T08:30:32+00:00, book20_bid_proxy_usdt=3132686, book20_ask_proxy_usdt=4007355, funding_indicative=0.000086, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=269202790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T08:30:02+00:00, last15m_closed_end=2026-11-10T08:30+00:00, prior8high=1159.070000, depth_time=2026-11-10T08:30:15+00:00, book20_bid_proxy_usdt=240767, book20_ask_proxy_usdt=289789, funding_indicative=0.000049, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.93%, turnover=2348385650. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
