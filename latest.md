# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T05:30:32Z**
- feed_generated_utc: 2026-11-10T05:30:34+00:00
- source_sha256: `a060390832945502963fc9e1a697462cc9e4d0c860cf115a18c586788273b44c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T05:30+00:00, close=74779.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T05:00+00:00, close=74754.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002502|-48.90|-54.52|-47.95|15406916|7.99|
|JCT_USDT|0.007486|-26.10|73.40|-25.15|27051107|4.01|
|ARB_USDT|0.172010|-6.53|7.95|-5.58|33790516|0.58|
|ZEC_USDT|1153.440000|-5.89|-8.02|-4.94|2427807244|0.09|
|AAVE_USDT|127.040000|-4.73|-2.69|-3.78|13528782|1.57|
|QNT_USDT|191.380000|-4.32|-5.46|-3.37|36641798|0.52|
|DOT_USDT|0.853300|-4.22|-8.65|-3.27|10715282|1.17|
|DASH_USDT|45.900000|-3.61|-2.75|-2.66|14148684|2.18|
|PUMPFUN_USDT|0.003567|-3.12|-13.08|-2.17|7663452|2.80|
|INJ_USDT|7.991000|-2.27|14.01|-1.32|17978475|1.25|
|SOL_USDT|86.080000|-2.05|-7.94|-1.10|647422457|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.040000|126.070000|127.040000|1.09|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002502|0.002357|0.002501|0.32|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172010|0.170290|0.172010|1.30|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.900000|45.750000|45.900000|0.25|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.853300|0.846300|0.853400|0.71|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.991000|7.956000|7.992000|0.30|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007486|0.007526|0.007446|3.28|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003567|0.003556|0.003567|0.75|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.380000|190.450000|191.380000|0.30|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.080000|85.470000|86.080000|1.08|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1153.440000|1142.950000|1153.550000|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=130.290000, depth_time=2026-11-10T05:30:15+00:00, book20_bid_proxy_usdt=400367, book20_ask_proxy_usdt=435832, funding_indicative=0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=13528782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=0.002790, depth_time=2026-11-10T05:30:07+00:00, book20_bid_proxy_usdt=82088, book20_ask_proxy_usdt=57212, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.90%, turnover=15406916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=0.172370, depth_time=2026-11-10T05:30:08+00:00, book20_bid_proxy_usdt=62596, book20_ask_proxy_usdt=70538, funding_indicative=-0.000002, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.53%, turnover=33790516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=46.350000, depth_time=2026-11-10T05:30:23+00:00, book20_bid_proxy_usdt=610411, book20_ask_proxy_usdt=566127, funding_indicative=0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=14148684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=0.854500, depth_time=2026-11-10T05:30:21+00:00, book20_bid_proxy_usdt=547711, book20_ask_proxy_usdt=512513, funding_indicative=0.000026, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.22%, turnover=10715282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=8.060000, depth_time=2026-11-10T05:30:28+00:00, book20_bid_proxy_usdt=89585, book20_ask_proxy_usdt=235810, funding_indicative=-0.000082, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=17978475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=0.008970, depth_time=2026-11-10T05:30:10+00:00, book20_bid_proxy_usdt=37856, book20_ask_proxy_usdt=39116, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-26.10%, turnover=27051107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=0.003602, depth_time=2026-11-10T05:30:22+00:00, book20_bid_proxy_usdt=2385941, book20_ask_proxy_usdt=2550924, funding_indicative=0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=7663452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=194.060000, depth_time=2026-11-10T05:30:18+00:00, book20_bid_proxy_usdt=86124, book20_ask_proxy_usdt=123276, funding_indicative=-0.000109, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=36641798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=86.360000, depth_time=2026-11-10T05:30:31+00:00, book20_bid_proxy_usdt=19871370, book20_ask_proxy_usdt=14459339, funding_indicative=0.000016, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=647422457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T05:30:02+00:00, last15m_closed_end=2026-11-10T05:30+00:00, prior8high=1159.000000, depth_time=2026-11-10T05:30:14+00:00, book20_bid_proxy_usdt=376627, book20_ask_proxy_usdt=114624, funding_indicative=0.000074, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.89%, turnover=2427807244. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
