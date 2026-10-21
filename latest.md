# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T05:00:28Z**
- feed_generated_utc: 2026-10-21T05:00:30+00:00
- source_sha256: `70cae27dfaaaac7895b069b1ece1e114dba36523376a2c549b91019cda51590d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T05:00+00:00, close=82776.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T05:00+00:00, close=82776.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.184920|-15.32|4.25|-15.55|10471391|5.41|
|BR_USDT|0.583410|-10.33|34.73|-10.56|34257579|3.26|
|XMR_USDT|576.450000|-7.05|9.19|-7.28|20916583|2.78|
|PHA_USDT|0.057170|-5.08|3.88|-5.31|7540321|1.75|
|TIA_USDT|0.613500|-4.27|6.27|-4.50|47306017|3.26|
|HBAR_USDT|0.083260|-2.66|-4.02|-2.89|19483931|1.20|
|AGT_USDT|0.062096|-2.47|283.85|-2.70|6576418|4.34|
|INJ_USDT|8.808000|-1.10|12.38|-1.33|58453502|1.14|
|SILVER_USDT|57.410000|-0.93|-3.33|-1.16|230412107|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062096|0.060783|0.062096|0.35|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.184920|0.184440|0.184920|0.82|N|Y/Y|Y/N|N|N|
|BR_USDT|0.583410|0.581680|0.583690|0.77|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.083260|0.083050|0.083260|1.22|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.808000|8.842000|8.808000|1.48|Y|N/N|N/N|N|N|
|PHA_USDT|0.057170|0.056320|0.057170|0.77|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.410000|57.420000|57.420000|1.43|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.613500|0.608800|0.613500|0.60|N|Y/Y|Y/Y|N|N|
|XMR_USDT|576.450000|571.180000|575.320000|0.96|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=0.064103, depth_time=2026-10-21T05:00:17+00:00, book20_bid_proxy_usdt=3848, book20_ask_proxy_usdt=4955, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=6576418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=0.188200, depth_time=2026-10-21T05:00:07+00:00, book20_bid_proxy_usdt=25592, book20_ask_proxy_usdt=35795, funding_indicative=-0.000045, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-15.32%, turnover=10471391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=0.640830, depth_time=2026-10-21T05:00:10+00:00, book20_bid_proxy_usdt=3221, book20_ask_proxy_usdt=3045, funding_indicative=0.000050, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.33%, turnover=34257579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=0.083770, depth_time=2026-10-21T05:00:19+00:00, book20_bid_proxy_usdt=1163927, book20_ask_proxy_usdt=561574, funding_indicative=0.000065, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=19483931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=9.153000, depth_time=2026-10-21T05:00:24+00:00, book20_bid_proxy_usdt=235800, book20_ask_proxy_usdt=227047, funding_indicative=0.000147, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=58453502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=0.058840, depth_time=2026-10-21T05:00:14+00:00, book20_bid_proxy_usdt=88412, book20_ask_proxy_usdt=69354, funding_indicative=0.000026, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.08%, turnover=7540321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=57.720000, depth_time=2026-10-21T05:00:26+00:00, book20_bid_proxy_usdt=40689539, book20_ask_proxy_usdt=39570501, funding_indicative=0.000018, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=230412107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=0.621800, depth_time=2026-10-21T05:00:17+00:00, book20_bid_proxy_usdt=206413, book20_ask_proxy_usdt=231162, funding_indicative=-0.000078, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.27%, turnover=47306017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T05:00:02+00:00, last15m_closed_end=2026-10-21T05:00+00:00, prior8high=581.000000, depth_time=2026-10-21T05:00:12+00:00, book20_bid_proxy_usdt=18278, book20_ask_proxy_usdt=9545, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.05%, turnover=20916583. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
