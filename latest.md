# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T03:00:24Z**
- feed_generated_utc: 2026-10-14T03:00:27+00:00
- source_sha256: `186b1ee4c1c36d93a9b73f5bde63d36fdac90514edcb631de5077b240d1e7df8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T03:00+00:00, close=83609.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T03:00+00:00, close=83609.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.060030|-14.97|37.36|-15.24|24018094|1.67|
|OGN_USDT|0.034030|-5.34|51.85|-5.61|5025557|5.88|
|STRK_USDT|0.084140|-3.20|61.21|-3.47|29932078|1.19|
|W_USDT|0.016397|-2.41|12.98|-2.68|7178309|2.44|
|TIA_USDT|0.576000|-1.53|20.93|-1.80|46061404|1.74|
|DOT_USDT|1.168500|-1.35|-2.73|-1.62|19638199|0.86|
|MAGIC_USDT|0.117040|-1.35|71.81|-1.62|5988993|0.85|
|XLM_USDT|0.190200|-0.93|-10.98|-1.20|8949471|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.168500|1.159300|1.168500|1.60|N|Y/Y|Y/Y|N|N|
|MAGIC_USDT|0.117040|0.115170|0.117040|0.84|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034030|0.033730|0.034030|0.54|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.084140|0.084230|0.084200|1.83|Y|Y/Y|Y/Y|N|Y|
|S_USDT|0.060030|0.057350|0.060030|1.88|N|N/N|N/N|N|N|
|TIA_USDT|0.576000|0.566300|0.575600|0.50|N|Y/Y|N/N|N|N|
|W_USDT|0.016397|0.016415|0.016400|0.48|N|Y/Y|Y/Y|N|N|
|XLM_USDT|0.190200|0.189470|0.190200|0.63|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=1.178800, depth_time=2026-10-14T03:00:19+00:00, book20_bid_proxy_usdt=201705, book20_ask_proxy_usdt=189464, funding_indicative=0.000092, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=19638199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.122210, depth_time=2026-10-14T03:00:21+00:00, book20_bid_proxy_usdt=172721, book20_ask_proxy_usdt=160521, funding_indicative=-0.000129, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=5988993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.034900, depth_time=2026-10-14T03:00:04+00:00, book20_bid_proxy_usdt=131524, book20_ask_proxy_usdt=144578, funding_indicative=-0.000203, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.34%, turnover=5025557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.086310, depth_time=2026-10-14T03:00:12+00:00, book20_bid_proxy_usdt=410926, book20_ask_proxy_usdt=206064, funding_indicative=0.000013, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=29932078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.059520, depth_time=2026-10-14T03:00:07+00:00, book20_bid_proxy_usdt=86596, book20_ask_proxy_usdt=50881, funding_indicative=-0.000011, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.97%, turnover=24018094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.578700, depth_time=2026-10-14T03:00:14+00:00, book20_bid_proxy_usdt=276254, book20_ask_proxy_usdt=139601, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=46061404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.017209, depth_time=2026-10-14T03:00:12+00:00, book20_bid_proxy_usdt=16802, book20_ask_proxy_usdt=27553, funding_indicative=-0.000326, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=7178309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T03:00:01+00:00, last15m_closed_end=2026-10-14T03:00+00:00, prior8high=0.191910, depth_time=2026-10-14T03:00:23+00:00, book20_bid_proxy_usdt=156829, book20_ask_proxy_usdt=131562, funding_indicative=0.000087, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=8949471. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
