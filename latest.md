# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T12:30:33Z**
- feed_generated_utc: 2026-10-23T12:30:36+00:00
- source_sha256: `171378b3062f49f6a4f6997c2ed02aa8cc7adc9b488f73ae15057f38882bbfbc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T12:30+00:00, close=81677.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.431360|-14.07|82.43|-14.10|6575881|3.95|
|LIT_USDT|3.378800|-6.51|9.29|-6.54|8710004|0.30|
|QNT_USDT|182.500000|-4.30|-12.22|-4.33|54425886|0.55|
|TIA_USDT|0.548200|-3.55|-9.01|-3.58|25161891|1.82|
|SILVER_USDT|53.950000|-2.37|-5.58|-2.40|327382585|1.85|
|STRK_USDT|0.053240|-2.06|-44.74|-2.09|12215012|1.88|
|ARB_USDT|0.180390|-1.76|-5.02|-1.79|24913613|0.55|
|OP_USDT|0.118180|-1.39|-14.89|-1.42|6206215|0.85|
|PUMPFUN_USDT|0.004628|-1.08|2.25|-1.11|40205274|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180390|0.179250|0.180390|1.66|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.378800|3.344500|3.378800|3.57|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.431360|0.426720|0.431200|2.06|N|Y/Y|N/N|Y|N|
|OP_USDT|0.118180|0.116880|0.118180|2.97|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004628|0.004525|0.004628|1.86|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.500000|180.980000|182.500000|2.02|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.950000|53.890000|53.940000|5.59|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053240|0.051150|0.053240|0.87|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.548200|0.544800|0.548200|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=0.181560, depth_time=2026-10-23T12:30:27+00:00, book20_bid_proxy_usdt=68736, book20_ask_proxy_usdt=44007, funding_indicative=-0.000011, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=24913613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=3.402200, depth_time=2026-10-23T12:30:11+00:00, book20_bid_proxy_usdt=19433, book20_ask_proxy_usdt=19468, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=8710004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T12:30:03+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=0.509490, depth_time=2026-10-23T12:30:09+00:00, book20_bid_proxy_usdt=2046, book20_ask_proxy_usdt=6324, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.07%, turnover=6575881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=0.118640, depth_time=2026-10-23T12:30:30+00:00, book20_bid_proxy_usdt=113440, book20_ask_proxy_usdt=130998, funding_indicative=0.000031, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=6206215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=0.004674, depth_time=2026-10-23T12:30:32+00:00, book20_bid_proxy_usdt=1143882, book20_ask_proxy_usdt=1891940, funding_indicative=0.000025, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=40205274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=183.550000, depth_time=2026-10-23T12:30:15+00:00, book20_bid_proxy_usdt=57635, book20_ask_proxy_usdt=63028, funding_indicative=-0.000178, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=54425886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T12:30:03+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=54.210000, depth_time=2026-10-23T12:30:22+00:00, book20_bid_proxy_usdt=33080012, book20_ask_proxy_usdt=28837491, funding_indicative=0.000022, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=327382585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=0.052950, depth_time=2026-10-23T12:30:24+00:00, book20_bid_proxy_usdt=586151, book20_ask_proxy_usdt=583227, funding_indicative=0.000019, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=12215012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T12:29:59+00:00, last15m_closed_end=2026-10-23T12:30+00:00, prior8high=0.552100, depth_time=2026-10-23T12:30:15+00:00, book20_bid_proxy_usdt=242525, book20_ask_proxy_usdt=352720, funding_indicative=0.000031, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=25161891. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
