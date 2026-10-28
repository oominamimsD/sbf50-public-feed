# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T15:45:37Z**
- feed_generated_utc: 2026-10-28T15:45:41+00:00
- source_sha256: `ed39455d588ab5fd53d0b754861f8d458666e97fb1a0590a1f86917dc2d65c90`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T15:45+00:00, close=80592.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T15:00+00:00, close=80572.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.079260|-12.98|6.09|-13.05|11660676|6.30|
|AKE_USDT|0.019236|-8.94|-38.13|-9.01|6802714|4.68|
|ENA_USDT|0.196340|-7.72|3.40|-7.79|86378002|0.51|
|INJ_USDT|7.770000|-5.15|-9.65|-5.22|24803061|1.29|
|DASH_USDT|53.180000|-1.82|6.48|-1.89|14237888|1.88|
|PUMPFUN_USDT|0.004211|-1.72|-6.65|-1.79|13477124|2.37|
|QNT_USDT|194.610000|-1.65|-0.28|-1.72|67976880|0.51|
|ASTER_USDT|0.702400|-1.48|-1.62|-1.55|5740755|1.42|
|SILVER_USDT|53.840000|-1.46|-7.09|-1.53|254163368|1.86|
|ADA_USDT|0.203000|-1.26|-8.31|-1.33|38694474|4.93|
|ZEC_USDT|1276.740000|-1.23|7.19|-1.30|1595084959|0.08|
|UNI_USDT|7.084000|-1.04|-2.57|-1.11|14628391|1.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.203000|0.201100|0.202900|0.51|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.019236|0.019128|0.019236|0.67|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.702400|0.701400|0.702400|0.48|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.079260|0.078520|0.079260|0.68|N|Y/Y|Y/N|Y|N|
|DASH_USDT|53.180000|52.690000|53.170000|0.45|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.196340|0.192810|0.196340|0.53|N|Y/Y|Y/N|Y|N|
|INJ_USDT|7.770000|7.748000|7.771000|1.04|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004211|0.004162|0.004210|1.25|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.610000|192.380000|194.550000|0.96|N|Y/Y|N/N|Y|N|
|SILVER_USDT|53.840000|53.600000|53.850000|0.98|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.084000|6.969000|7.086000|1.57|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1276.740000|1268.350000|1276.480000|1.08|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=0.203700, depth_time=2026-10-28T15:45:30+00:00, book20_bid_proxy_usdt=6402144, book20_ask_proxy_usdt=6049395, funding_indicative=-0.000049, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=38694474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=0.019953, depth_time=2026-10-28T15:45:11+00:00, book20_bid_proxy_usdt=3116, book20_ask_proxy_usdt=4834, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.94%, turnover=6802714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=0.706300, depth_time=2026-10-28T15:45:26+00:00, book20_bid_proxy_usdt=1129060, book20_ask_proxy_usdt=585907, funding_indicative=0.000025, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=5740755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=0.080780, depth_time=2026-10-28T15:45:08+00:00, book20_bid_proxy_usdt=13010, book20_ask_proxy_usdt=8052, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.98%, turnover=11660676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=53.280000, depth_time=2026-10-28T15:45:18+00:00, book20_bid_proxy_usdt=1105507, book20_ask_proxy_usdt=672333, funding_indicative=0.000075, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=14237888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=0.199740, depth_time=2026-10-28T15:45:13+00:00, book20_bid_proxy_usdt=221185, book20_ask_proxy_usdt=138715, funding_indicative=-0.000042, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.72%, turnover=86378002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=7.877000, depth_time=2026-10-28T15:45:15+00:00, book20_bid_proxy_usdt=570383, book20_ask_proxy_usdt=261167, funding_indicative=0.000082, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.15%, turnover=24803061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=0.004262, depth_time=2026-10-28T15:45:20+00:00, book20_bid_proxy_usdt=1955646, book20_ask_proxy_usdt=1918695, funding_indicative=0.000033, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=13477124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=197.700000, depth_time=2026-10-28T15:45:23+00:00, book20_bid_proxy_usdt=73130, book20_ask_proxy_usdt=166817, funding_indicative=-0.000175, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=67976880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=54.240000, depth_time=2026-10-28T15:45:29+00:00, book20_bid_proxy_usdt=55449825, book20_ask_proxy_usdt=43769082, funding_indicative=0.000041, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=254163368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=7.083000, depth_time=2026-10-28T15:45:36+00:00, book20_bid_proxy_usdt=2349826, book20_ask_proxy_usdt=3015358, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=14628391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-28T15:45:03+00:00, last15m_closed_end=2026-10-28T15:45+00:00, prior8high=1292.460000, depth_time=2026-10-28T15:45:33+00:00, book20_bid_proxy_usdt=1100610, book20_ask_proxy_usdt=217710, funding_indicative=0.000085, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=1595084959. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
