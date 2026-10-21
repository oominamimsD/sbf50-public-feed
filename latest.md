# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T04:30:26Z**
- feed_generated_utc: 2026-10-21T04:30:29+00:00
- source_sha256: `bb7f95f1965d15156629c69cb58e9f7b1ea45e6c2823c913400e9ab6f1c9c24f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T04:30+00:00, close=82789.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.185510|-14.02|4.58|-14.27|10618170|2.16|
|BR_USDT|0.595670|-8.45|37.56|-8.70|34786206|3.70|
|XMR_USDT|579.540000|-6.55|9.78|-6.80|20738531|0.52|
|Q_USDT|0.115420|-5.97|180.64|-6.22|5033537|4.07|
|AGT_USDT|0.062201|-3.75|284.50|-4.00|6878253|0.48|
|PHA_USDT|0.056720|-1.90|3.07|-2.15|8357478|1.76|
|TIA_USDT|0.615800|-1.10|6.66|-1.35|48161778|1.62|
|SILVER_USDT|57.470000|-0.82|-3.23|-1.07|229512680|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062201|0.060783|0.062201|0.67|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.185510|0.185410|0.185510|1.81|N|Y/Y|Y/N|N|N|
|BR_USDT|0.595670|0.613570|0.595910|3.24|Y|Y/Y|N/N|N|N|
|PHA_USDT|0.056720|0.056540|0.056720|2.24|N|Y/Y|N/N|N|N|
|Q_USDT|0.115420|0.116120|0.115420|1.91|Y|Y/Y|N/N|N|N|
|SILVER_USDT|57.470000|57.440000|57.460000|0.82|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.615800|0.608800|0.615800|0.71|N|Y/Y|Y/Y|N|N|
|XMR_USDT|579.540000|571.180000|579.540000|0.25|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=0.064559, depth_time=2026-10-21T04:30:15+00:00, book20_bid_proxy_usdt=12058, book20_ask_proxy_usdt=9453, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=6878253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=0.188200, depth_time=2026-10-21T04:30:07+00:00, book20_bid_proxy_usdt=27173, book20_ask_proxy_usdt=22854, funding_indicative=-0.000024, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.02%, turnover=10618170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=0.640830, depth_time=2026-10-21T04:30:11+00:00, book20_bid_proxy_usdt=3450, book20_ask_proxy_usdt=2695, funding_indicative=0.000023, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.45%, turnover=34786206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=0.058840, depth_time=2026-10-21T04:30:21+00:00, book20_bid_proxy_usdt=60290, book20_ask_proxy_usdt=56946, funding_indicative=0.000030, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=8357478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=0.120677, depth_time=2026-10-21T04:30:15+00:00, book20_bid_proxy_usdt=15730, book20_ask_proxy_usdt=18016, funding_indicative=-0.000242, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.97%, turnover=5033537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=57.720000, depth_time=2026-10-21T04:30:25+00:00, book20_bid_proxy_usdt=32334396, book20_ask_proxy_usdt=36170999, funding_indicative=0.000016, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=229512680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=0.621500, depth_time=2026-10-21T04:30:21+00:00, book20_bid_proxy_usdt=196497, book20_ask_proxy_usdt=190974, funding_indicative=-0.000059, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=48161778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T04:30:01+00:00, last15m_closed_end=2026-10-21T04:30+00:00, prior8high=582.810000, depth_time=2026-10-21T04:30:12+00:00, book20_bid_proxy_usdt=27474, book20_ask_proxy_usdt=13822, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.55%, turnover=20738531. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
