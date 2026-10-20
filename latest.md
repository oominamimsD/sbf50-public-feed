# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T20:00:24Z**
- feed_generated_utc: 2026-10-20T20:00:27+00:00
- source_sha256: `49e00c9d306f8c0c0f9426dde94a7650361b562ce4f9bf8e9cad7a4a73a3e152`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.678100|-9.27|-14.05|-9.27|28249983|2.38|
|BAT_USDT|0.199540|-8.63|12.49|-8.63|11141651|3.00|
|AGT_USDT|0.059465|-7.99|267.58|-7.99|7276863|2.19|
|SEI_USDT|0.060940|-3.54|-2.29|-3.54|6036078|1.64|
|TIA_USDT|0.621600|-3.01|7.67|-3.01|45434023|1.61|
|PHA_USDT|0.058460|-2.93|6.23|-2.93|17155528|1.71|
|DASH_USDT|49.580000|-2.20|-0.16|-2.20|9609334|2.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.059465|0.057751|0.059409|0.54|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.199540|0.201020|0.199540|0.63|N|Y/N|N/N|N|N|
|BTW_USDT|1.678100|1.664700|1.674600|0.90|N|Y/Y|Y/Y|N|N|
|DASH_USDT|49.580000|49.230000|49.580000|0.29|N|Y/Y|N/N|N|N|
|PHA_USDT|0.058460|0.057550|0.058460|1.47|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060940|0.060550|0.060940|0.78|N|N/N|Y/Y|N|N|
|TIA_USDT|0.621600|0.623400|0.621600|0.48|N|Y/N|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T20:00:02+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=0.063088, depth_time=2026-10-20T20:00:11+00:00, book20_bid_proxy_usdt=7169, book20_ask_proxy_usdt=5051, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.99%, turnover=7276863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T20:00:02+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=0.207560, depth_time=2026-10-20T20:00:10+00:00, book20_bid_proxy_usdt=15932, book20_ask_proxy_usdt=54482, funding_indicative=0.000096, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.63%, turnover=11141651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T20:00:02+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=1.754000, depth_time=2026-10-20T20:00:08+00:00, book20_bid_proxy_usdt=7731, book20_ask_proxy_usdt=16498, funding_indicative=-0.002532, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=28249983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-20T20:00:03+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=50.050000, depth_time=2026-10-20T20:00:22+00:00, book20_bid_proxy_usdt=898188, book20_ask_proxy_usdt=832189, funding_indicative=-0.000055, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=9609334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-20T20:00:02+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=0.058770, depth_time=2026-10-20T20:00:21+00:00, book20_bid_proxy_usdt=69394, book20_ask_proxy_usdt=68082, funding_indicative=0.000026, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=17155528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T20:00:03+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=0.061830, depth_time=2026-10-20T20:00:14+00:00, book20_bid_proxy_usdt=162288, book20_ask_proxy_usdt=207792, funding_indicative=0.000029, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=6036078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-20T20:00:02+00:00, last15m_closed_end=2026-10-20T20:00+00:00, prior8high=0.642600, depth_time=2026-10-20T20:00:19+00:00, book20_bid_proxy_usdt=335905, book20_ask_proxy_usdt=163751, funding_indicative=-0.000038, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=45434023. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
