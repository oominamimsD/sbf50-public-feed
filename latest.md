# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T03:15:24Z**
- feed_generated_utc: 2026-11-09T03:15:25+00:00
- source_sha256: `23dfc1f28c7bc0e903c8182bd9ea4b192d85e98e1ee4622d346eb63bb439e1c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T03:15+00:00, close=74974, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T03:00+00:00, close=75248.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.008411|-14.47|68.92|-13.08|65221860|7.14|
|ONE_USDT|0.001676|-14.41|43.90|-13.02|10874072|0.60|
|AKE_USDT|0.004998|-6.70|-45.43|-5.31|12103537|6.00|
|TAO_USDT|216.220000|-4.34|-7.92|-2.95|31246967|1.39|
|XRP_USDT|1.106300|-4.28|-11.48|-2.89|226575231|1.81|
|HYPE_USDT|74.500000|-3.78|-15.03|-2.39|40332971|0.13|
|DOT_USDT|0.865500|-2.85|-8.60|-1.46|6994388|1.16|
|LIT_USDT|3.114100|-2.48|-3.59|-1.09|12754445|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004998|0.004921|0.004998|0.95|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.865500|0.864500|0.865500|1.37|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.500000|74.059000|74.500000|0.55|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008411|0.008576|0.008411|0.85|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.114100|3.075700|3.114100|0.16|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001676|0.001686|0.001675|0.47|N|Y/Y|Y/N|Y|N|
|TAO_USDT|216.220000|216.670000|216.220000|0.91|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.106300|1.106800|1.106300|0.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=0.005250, depth_time=2026-11-09T03:15:12+00:00, book20_bid_proxy_usdt=41066, book20_ask_proxy_usdt=50404, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.70%, turnover=12103537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=0.875800, depth_time=2026-11-09T03:15:18+00:00, book20_bid_proxy_usdt=513256, book20_ask_proxy_usdt=323279, funding_indicative=0.000052, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=6994388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=75.332000, depth_time=2026-11-09T03:15:18+00:00, book20_bid_proxy_usdt=81019, book20_ask_proxy_usdt=114903, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.78%, turnover=40332971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=0.012446, depth_time=2026-11-09T03:15:07+00:00, book20_bid_proxy_usdt=18090, book20_ask_proxy_usdt=52661, funding_indicative=0.001240, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.47%, turnover=65221860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=3.158500, depth_time=2026-11-09T03:15:19+00:00, book20_bid_proxy_usdt=22594, book20_ask_proxy_usdt=20637, funding_indicative=-0.000027, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=12754445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=0.001739, depth_time=2026-11-09T03:15:09+00:00, book20_bid_proxy_usdt=10487, book20_ask_proxy_usdt=6803, funding_indicative=-0.000697, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.41%, turnover=10874072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=220.660000, depth_time=2026-11-09T03:15:13+00:00, book20_bid_proxy_usdt=128479, book20_ask_proxy_usdt=88686, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=31246967. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T03:15:01+00:00, last15m_closed_end=2026-11-09T03:15+00:00, prior8high=1.125700, depth_time=2026-11-09T03:15:16+00:00, book20_bid_proxy_usdt=2171772, book20_ask_proxy_usdt=1865294, funding_indicative=-0.000001, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.28%, turnover=226575231. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
