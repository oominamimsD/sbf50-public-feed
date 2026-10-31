# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T14:45:29Z**
- feed_generated_utc: 2026-10-31T14:45:32+00:00
- source_sha256: `449df5d795faa5a74cd1cdde5667f2e546269e78f498c6ee5ba3ddcc757549f2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T14:45+00:00, close=77493.7, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T14:00+00:00, close=77477.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011103|-41.31|-68.27|-41.20|11942238|4.50|
|Q_USDT|0.032730|-31.06|-72.34|-30.95|11779240|9.17|
|BEAT_USDT|0.097410|-7.36|34.19|-7.25|6951920|3.08|
|TRX_USDT|0.315440|-5.97|-4.22|-5.86|6696607|0.63|
|HYPE_USDT|86.933000|-5.85|10.87|-5.74|98842536|0.12|
|BTW_USDT|1.134000|-5.46|-33.38|-5.35|8181673|3.52|
|WLD_USDT|0.396900|-3.64|-25.45|-3.53|40382854|2.52|
|FET_USDT|0.161500|-3.06|-13.77|-2.95|5875765|6.19|
|DASH_USDT|48.470000|-1.16|-9.99|-1.05|7978174|2.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011103|0.011071|0.011116|1.50|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097410|0.097300|0.097410|0.57|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.134000|1.081300|1.134000|1.02|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.470000|47.750000|48.470000|4.80|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161500|0.160500|0.161500|0.19|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.933000|86.372000|86.933000|1.10|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032730|0.031490|0.032710|0.58|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.315440|0.315790|0.315450|2.10|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.396900|0.395200|0.396700|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T14:45:01+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=0.012053, depth_time=2026-10-31T14:45:09+00:00, book20_bid_proxy_usdt=10398, book20_ask_proxy_usdt=6995, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-41.31%, turnover=11942238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T14:45:02+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=0.100690, depth_time=2026-10-31T14:45:13+00:00, book20_bid_proxy_usdt=11278, book20_ask_proxy_usdt=14072, funding_indicative=0.000109, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.36%, turnover=6951920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T14:45:02+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=1.176700, depth_time=2026-10-31T14:45:21+00:00, book20_bid_proxy_usdt=9201, book20_ask_proxy_usdt=12286, funding_indicative=-0.000200, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.46%, turnover=8181673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T14:45:02+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=48.210000, depth_time=2026-10-31T14:45:28+00:00, book20_bid_proxy_usdt=621794, book20_ask_proxy_usdt=691573, funding_indicative=-0.000139, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=7978174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T14:45:02+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=0.161800, depth_time=2026-10-31T14:45:25+00:00, book20_bid_proxy_usdt=1615343, book20_ask_proxy_usdt=804361, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=5875765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T14:45:01+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=88.704000, depth_time=2026-10-31T14:45:17+00:00, book20_bid_proxy_usdt=138266, book20_ask_proxy_usdt=91388, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=98842536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T14:45:01+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=0.032810, depth_time=2026-10-31T14:45:11+00:00, book20_bid_proxy_usdt=55552, book20_ask_proxy_usdt=34791, funding_indicative=-0.000481, next_funding_utc=2026-10-31T15:00:00+00:00, funding_cycle_h=1, 24h_change=-31.06%, turnover=11779240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T14:45:02+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=0.322470, depth_time=2026-10-31T14:45:16+00:00, book20_bid_proxy_usdt=53102, book20_ask_proxy_usdt=73657, funding_indicative=-0.000661, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.97%, turnover=6696607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T14:45:02+00:00, last15m_closed_end=2026-10-31T14:45+00:00, prior8high=0.399000, depth_time=2026-10-31T14:45:23+00:00, book20_bid_proxy_usdt=3306641, book20_ask_proxy_usdt=3347231, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=40382854. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
