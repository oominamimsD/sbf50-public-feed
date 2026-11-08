# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T15:30:24Z**
- feed_generated_utc: 2026-11-08T15:30:25+00:00
- source_sha256: `4fb2af7505a1d51efa850f980496e6c802811260c58a0ea4a55de1ae75c07ee2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T15:30+00:00, close=76026.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T15:00+00:00, close=76006.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030896|-7.21|76.33|-7.60|15273977|0.32|
|ONE_USDT|0.001910|-6.19|62.71|-6.58|22277979|0.52|
|TIA_USDT|0.421900|-4.46|-13.91|-4.85|7099576|2.37|
|WLD_USDT|0.327100|-2.53|-19.11|-2.92|24528381|3.06|
|AAVE_USDT|129.210000|-2.28|-4.64|-2.67|9445680|0.77|
|ENA_USDT|0.154590|-2.26|-20.31|-2.65|24591918|0.65|
|LINK_USDT|10.732000|-1.03|-7.25|-1.42|59260900|0.93|
|SUI_USDT|0.851100|-0.70|-5.64|-1.09|24763465|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.210000|128.470000|129.210000|1.03|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.154590|0.152750|0.154630|0.46|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030896|0.029797|0.030896|0.47|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.732000|10.691000|10.732000|0.89|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001910|0.001818|0.001910|1.21|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.851100|0.845000|0.851000|0.99|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.421900|0.419200|0.421900|1.02|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327100|0.323500|0.327100|0.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=131.400000, depth_time=2026-11-08T15:30:09+00:00, book20_bid_proxy_usdt=320955, book20_ask_proxy_usdt=639003, funding_indicative=0.000073, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=9445680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=0.155690, depth_time=2026-11-08T15:30:15+00:00, book20_bid_proxy_usdt=395486, book20_ask_proxy_usdt=236201, funding_indicative=-0.000039, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=24591918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=0.031239, depth_time=2026-11-08T15:30:06+00:00, book20_bid_proxy_usdt=5145, book20_ask_proxy_usdt=5156, funding_indicative=0.001001, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.21%, turnover=15273977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=10.788000, depth_time=2026-11-08T15:30:17+00:00, book20_bid_proxy_usdt=405548, book20_ask_proxy_usdt=470828, funding_indicative=0.000016, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=59260900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=0.001958, depth_time=2026-11-08T15:30:09+00:00, book20_bid_proxy_usdt=13288, book20_ask_proxy_usdt=8850, funding_indicative=-0.001274, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.19%, turnover=22277979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=0.859000, depth_time=2026-11-08T15:30:20+00:00, book20_bid_proxy_usdt=1798759, book20_ask_proxy_usdt=1744201, funding_indicative=0.000043, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.70%, turnover=24763465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=0.425000, depth_time=2026-11-08T15:30:07+00:00, book20_bid_proxy_usdt=235682, book20_ask_proxy_usdt=238593, funding_indicative=0.000026, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=7099576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T15:30:00+00:00, last15m_closed_end=2026-11-08T15:30+00:00, prior8high=0.328300, depth_time=2026-11-08T15:30:13+00:00, book20_bid_proxy_usdt=3548402, book20_ask_proxy_usdt=3545656, funding_indicative=-0.000070, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=24528381. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
