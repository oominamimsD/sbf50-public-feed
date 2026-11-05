# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T00:45:27Z**
- feed_generated_utc: 2026-11-05T00:45:29+00:00
- source_sha256: `5d34a70ff9dd806e5bd58e9aa70b6fb6f8bcd22cd85f6e69b134676c52c616f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T00:45+00:00, close=80730.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002443|-13.06|-87.84|-13.63|16533183|4.10|
|TRUMPOFFICIAL_USDT|1.248000|-12.35|-26.97|-12.92|28006106|8.02|
|VVV_USDT|21.164000|-8.59|-11.13|-9.16|5235476|3.78|
|IDOL_USDT|0.021511|-8.33|148.48|-8.90|6269006|1.40|
|BTW_USDT|1.020200|-7.17|-41.30|-7.74|6179776|0.98|
|EVAA_USDT|1.522600|-7.02|2.53|-7.59|5058806|4.60|
|PUMPFUN_USDT|0.004281|-3.79|1.75|-4.36|17834846|2.34|
|ZRO_USDT|1.823300|-2.22|6.50|-2.79|11139044|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002443|0.002379|0.002445|0.50|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.020200|1.015400|1.020100|2.04|N|Y/Y|Y/N|N|N|
|EVAA_USDT|1.522600|1.526800|1.522400|0.51|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021511|0.021242|0.021520|0.23|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004281|0.004236|0.004281|2.85|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.248000|1.246000|1.248000|2.15|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.164000|20.977000|21.164000|1.24|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.823300|1.811900|1.823300|1.36|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=0.002595, depth_time=2026-11-05T00:45:08+00:00, book20_bid_proxy_usdt=57803, book20_ask_proxy_usdt=58442, funding_indicative=-0.001022, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.06%, turnover=16533183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=1.044500, depth_time=2026-11-05T00:45:16+00:00, book20_bid_proxy_usdt=30014, book20_ask_proxy_usdt=28444, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.17%, turnover=6179776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=1.595600, depth_time=2026-11-05T00:45:21+00:00, book20_bid_proxy_usdt=12091, book20_ask_proxy_usdt=17324, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.02%, turnover=5058806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=0.022404, depth_time=2026-11-05T00:45:16+00:00, book20_bid_proxy_usdt=7720, book20_ask_proxy_usdt=7313, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.33%, turnover=6269006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=0.004318, depth_time=2026-11-05T00:45:23+00:00, book20_bid_proxy_usdt=2717231, book20_ask_proxy_usdt=2145261, funding_indicative=0.000004, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=17834846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=1.286000, depth_time=2026-11-05T00:45:10+00:00, book20_bid_proxy_usdt=1445126, book20_ask_proxy_usdt=1063818, funding_indicative=-0.000439, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.35%, turnover=28006106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=22.501000, depth_time=2026-11-05T00:45:13+00:00, book20_bid_proxy_usdt=21592, book20_ask_proxy_usdt=40144, funding_indicative=-0.000392, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.59%, turnover=5235476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T00:45:01+00:00, last15m_closed_end=2026-11-05T00:45+00:00, prior8high=1.856300, depth_time=2026-11-05T00:45:26+00:00, book20_bid_proxy_usdt=33565, book20_ask_proxy_usdt=64519, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=11139044. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
