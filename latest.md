# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T05:30:25Z**
- feed_generated_utc: 2026-10-20T05:30:28+00:00
- source_sha256: `6da4c88a76d57e329b78b1c3fc6beb39e10437da362cefc70389b50fe455b42c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T05:30+00:00, close=81951.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T05:00+00:00, close=82060.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.117495|-6.73|281.58|-6.77|11785228|5.03|
|CT_USDT|0.309610|-6.21|-9.50|-6.25|5417011|1.94|
|SAND_USDT|0.056940|-3.71|-8.29|-3.75|8727088|1.76|
|ZRO_USDT|1.845500|-2.97|-18.37|-3.01|7639012|0.54|
|NEAR_USDT|4.797000|-2.18|-13.55|-2.22|166488688|2.08|
|PUMPFUN_USDT|0.004401|-1.23|-17.10|-1.27|29698700|2.27|
|TAO_USDT|265.580000|-1.01|-7.23|-1.05|52197797|0.75|
|SEI_USDT|0.060060|-1.00|-9.50|-1.04|6857698|1.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.309610|0.302430|0.309990|1.79|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.797000|4.796000|4.797000|0.81|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004401|0.004392|0.004401|2.02|N|N/N|N/N|N|N|
|Q_USDT|0.117495|0.113888|0.117649|4.85|N|Y/Y|N/N|N|N|
|SAND_USDT|0.056940|0.056680|0.056940|1.10|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.060060|0.060200|0.060060|3.90|Y|N/N|Y/Y|N|N|
|TAO_USDT|265.580000|266.390000|265.530000|2.55|Y|Y/N|Y/Y|N|N|
|ZRO_USDT|1.845500|1.849300|1.845100|2.55|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=0.337010, depth_time=2026-10-20T05:30:10+00:00, book20_bid_proxy_usdt=9631, book20_ask_proxy_usdt=9611, funding_indicative=-0.002605, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.21%, turnover=5417011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=4.872000, depth_time=2026-10-20T05:30:17+00:00, book20_bid_proxy_usdt=3809078, book20_ask_proxy_usdt=2302985, funding_indicative=0.000016, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=166488688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=0.004489, depth_time=2026-10-20T05:30:20+00:00, book20_bid_proxy_usdt=1571710, book20_ask_proxy_usdt=1312065, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=29698700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=0.133766, depth_time=2026-10-20T05:30:08+00:00, book20_bid_proxy_usdt=15932, book20_ask_proxy_usdt=17484, funding_indicative=-0.000213, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.73%, turnover=11785228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=0.058410, depth_time=2026-10-20T05:30:13+00:00, book20_bid_proxy_usdt=663796, book20_ask_proxy_usdt=1132283, funding_indicative=-0.001832, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=8727088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=0.061300, depth_time=2026-10-20T05:30:24+00:00, book20_bid_proxy_usdt=211098, book20_ask_proxy_usdt=159597, funding_indicative=0.000044, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=6857698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=269.360000, depth_time=2026-10-20T05:30:22+00:00, book20_bid_proxy_usdt=68160, book20_ask_proxy_usdt=85169, funding_indicative=0.000040, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=52197797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T05:30:01+00:00, last15m_closed_end=2026-10-20T05:30+00:00, prior8high=1.880400, depth_time=2026-10-20T05:30:15+00:00, book20_bid_proxy_usdt=42141, book20_ask_proxy_usdt=56336, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=7639012. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
