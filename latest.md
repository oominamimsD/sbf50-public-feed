# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T03:45:29Z**
- feed_generated_utc: 2026-10-23T03:45:31+00:00
- source_sha256: `1d2a6d2aa69c89b0a021e2cf712ccc2973e379cca62c02305d1edeb57445cac5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T03:45+00:00, close=81896.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T03:00+00:00, close=81942.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004207|-8.70|111.93|-8.99|9482986|4.75|
|LIT_USDT|3.479900|-3.71|12.56|-4.00|11142613|0.29|
|PHA_USDT|0.060350|-2.73|19.45|-3.02|8167281|3.31|
|STRK_USDT|0.053060|-2.39|-44.93|-2.68|12104142|1.89|
|SILVER_USDT|54.120000|-2.06|-5.28|-2.35|372821012|1.85|
|TIA_USDT|0.563400|-0.87|-6.48|-1.16|23765093|1.77|
|ZEC_USDT|1223.630000|-0.86|3.72|-1.15|1924739736|0.08|
|XAU_USDT|4024.840000|-0.85|-3.15|-1.14|769696404|0.03|
|XAUT_USDT|4023.240000|-0.76|-2.93|-1.05|288460073|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004207|0.004215|0.004198|3.54|Y|Y/Y|N/N|Y|N|
|LIT_USDT|3.479900|3.413500|3.479900|0.94|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.060350|0.059190|0.060350|0.10|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.120000|53.570000|54.130000|0.35|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053060|0.052520|0.053060|0.78|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.563400|0.555200|0.563600|1.10|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4023.240000|3994.260000|4023.240000|0.49|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4024.840000|3989.000000|4025.130000|0.45|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1223.630000|1210.790000|1223.820000|0.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=0.004440, depth_time=2026-10-23T03:45:08+00:00, book20_bid_proxy_usdt=34901, book20_ask_proxy_usdt=42353, funding_indicative=0.000069, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.70%, turnover=9482986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=3.544400, depth_time=2026-10-23T03:45:06+00:00, book20_bid_proxy_usdt=21697, book20_ask_proxy_usdt=23969, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=11142613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=0.060590, depth_time=2026-10-23T03:45:12+00:00, book20_bid_proxy_usdt=72621, book20_ask_proxy_usdt=69723, funding_indicative=-0.000398, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=8167281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=54.500000, depth_time=2026-10-23T03:45:19+00:00, book20_bid_proxy_usdt=37134275, book20_ask_proxy_usdt=33896304, funding_indicative=0.000087, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=372821012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=0.053500, depth_time=2026-10-23T03:45:16+00:00, book20_bid_proxy_usdt=532186, book20_ask_proxy_usdt=594241, funding_indicative=0.000022, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=12104142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=0.567500, depth_time=2026-10-23T03:45:21+00:00, book20_bid_proxy_usdt=313894, book20_ask_proxy_usdt=334460, funding_indicative=0.000002, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=23765093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=4030.690000, depth_time=2026-10-23T03:45:27+00:00, book20_bid_proxy_usdt=115397, book20_ask_proxy_usdt=211579, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.76%, turnover=288460073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=4032.600000, depth_time=2026-10-23T03:45:26+00:00, book20_bid_proxy_usdt=554086, book20_ask_proxy_usdt=966059, funding_indicative=0.000086, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=769696404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T03:45:02+00:00, last15m_closed_end=2026-10-23T03:45+00:00, prior8high=1244.740000, depth_time=2026-10-23T03:45:24+00:00, book20_bid_proxy_usdt=163262, book20_ask_proxy_usdt=170220, funding_indicative=0.000007, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=1924739736. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
