# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T11:15:29Z**
- feed_generated_utc: 2026-11-08T11:15:31+00:00
- source_sha256: `00edf2d8b2db85037c50b30600e44e074f8fe800825bec93c2ff7fdb956100ed`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T11:15+00:00, close=75923.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T11:00+00:00, close=75861.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001883|-7.55|60.35|-7.81|25587702|2.66|
|IDOL_USDT|0.031428|-5.61|79.37|-5.87|16241293|1.27|
|TIA_USDT|0.425400|-3.66|-13.20|-3.92|7218456|2.35|
|ENA_USDT|0.153220|-3.13|-21.02|-3.39|28931595|0.65|
|WLD_USDT|0.327800|-2.32|-18.94|-2.58|22735890|3.05|
|AAVE_USDT|130.510000|-1.30|-3.68|-1.56|9897614|0.77|
|SUI_USDT|0.848500|-1.00|-5.93|-1.26|21422533|1.18|
|ADA_USDT|0.180000|-0.88|-7.02|-1.14|9425459|5.55|
|LINK_USDT|10.755000|-0.82|-7.05|-1.08|61569207|0.93|
|DOGE_USDT|0.071000|-0.81|-6.13|-1.07|39205133|1.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.510000|129.470000|130.510000|0.48|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180000|0.178900|0.180000|0.96|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.071000|0.070450|0.070990|1.22|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153220|0.152210|0.153210|7.14|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.031428|0.032213|0.031330|4.30|Y|N/N|N/N|Y|N|
|LINK_USDT|10.755000|10.704000|10.755000|1.36|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001883|0.001898|0.001882|1.23|N|Y/N|N/N|Y|N|
|SUI_USDT|0.848500|0.846400|0.848900|1.20|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.425400|0.422800|0.425400|0.28|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327800|0.325700|0.327800|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=130.800000, depth_time=2026-11-08T11:15:18+00:00, book20_bid_proxy_usdt=340635, book20_ask_proxy_usdt=646053, funding_indicative=0.000049, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=9897614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.180200, depth_time=2026-11-08T11:15:23+00:00, book20_bid_proxy_usdt=8490172, book20_ask_proxy_usdt=9131578, funding_indicative=-0.000069, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=9425459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.071130, depth_time=2026-11-08T11:15:28+00:00, book20_bid_proxy_usdt=3974716, book20_ask_proxy_usdt=6507039, funding_indicative=0.000087, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=39205133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.154340, depth_time=2026-11-08T11:15:14+00:00, book20_bid_proxy_usdt=166852, book20_ask_proxy_usdt=211169, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=28931595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.033931, depth_time=2026-11-08T11:15:09+00:00, book20_bid_proxy_usdt=4541, book20_ask_proxy_usdt=4464, funding_indicative=0.000593, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.61%, turnover=16241293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=10.775000, depth_time=2026-11-08T11:15:26+00:00, book20_bid_proxy_usdt=541928, book20_ask_proxy_usdt=417405, funding_indicative=0.000025, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=61569207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.002228, depth_time=2026-11-08T11:15:07+00:00, book20_bid_proxy_usdt=13009, book20_ask_proxy_usdt=7562, funding_indicative=-0.001882, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.55%, turnover=25587702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.851600, depth_time=2026-11-08T11:15:20+00:00, book20_bid_proxy_usdt=1761035, book20_ask_proxy_usdt=1831739, funding_indicative=0.000008, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=21422533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.427500, depth_time=2026-11-08T11:15:10+00:00, book20_bid_proxy_usdt=226819, book20_ask_proxy_usdt=408218, funding_indicative=0.000023, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=7218456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T11:15:01+00:00, last15m_closed_end=2026-11-08T11:15+00:00, prior8high=0.328600, depth_time=2026-11-08T11:15:15+00:00, book20_bid_proxy_usdt=3798740, book20_ask_proxy_usdt=4636185, funding_indicative=-0.000048, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=22735890. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
