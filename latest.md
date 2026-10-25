# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T06:15:22Z**
- feed_generated_utc: 2026-10-25T06:15:25+00:00
- source_sha256: `8a6143647aad923a58f151b4eaa28945cc74d22a79c91e061c4b8fb13575d48b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T06:15+00:00, close=80604.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T06:00+00:00, close=80572.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.056450|-16.24|82.39|-17.29|13765752|1.77|
|BIRB_USDT|0.083290|-14.71|71.66|-15.76|7021886|2.40|
|IRYS_USDT|0.041650|-9.55|226.41|-10.60|33866455|2.40|
|STRK_USDT|0.045880|-1.81|-30.64|-2.86|8726978|2.18|
|DOT_USDT|1.029200|-0.95|-7.89|-2.00|11701921|0.97|
|SUI_USDT|0.919100|-0.63|-6.38|-1.68|64661240|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.083290|0.081770|0.083490|1.00|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.029200|1.032500|1.029200|3.88|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.041650|0.039230|0.041570|0.67|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.056450|0.054500|0.056450|0.71|N|Y/N|N/N|Y|N|
|STRK_USDT|0.045880|0.045690|0.045870|2.26|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.919100|0.916200|0.919200|3.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T06:15:03+00:00, last15m_closed_end=2026-10-25T06:15+00:00, prior8high=0.091370, depth_time=2026-10-25T06:15:11+00:00, book20_bid_proxy_usdt=11612, book20_ask_proxy_usdt=21075, funding_indicative=-0.011615, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.71%, turnover=7021886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T06:15:03+00:00, last15m_closed_end=2026-10-25T06:15+00:00, prior8high=1.043200, depth_time=2026-10-25T06:15:19+00:00, book20_bid_proxy_usdt=273543, book20_ask_proxy_usdt=486511, funding_indicative=-0.000107, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=11701921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T06:15:03+00:00, last15m_closed_end=2026-10-25T06:15+00:00, prior8high=0.049460, depth_time=2026-10-25T06:15:14+00:00, book20_bid_proxy_usdt=37756, book20_ask_proxy_usdt=35585, funding_indicative=-0.001932, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-9.55%, turnover=33866455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T06:15:03+00:00, last15m_closed_end=2026-10-25T06:15+00:00, prior8high=0.063890, depth_time=2026-10-25T06:15:09+00:00, book20_bid_proxy_usdt=64711, book20_ask_proxy_usdt=30907, funding_indicative=-0.001514, next_funding_utc=2026-10-25T07:00:00+00:00, funding_cycle_h=1, 24h_change=-16.24%, turnover=13765752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T06:15:03+00:00, last15m_closed_end=2026-10-25T06:15+00:00, prior8high=0.047320, depth_time=2026-10-25T06:15:16+00:00, book20_bid_proxy_usdt=716730, book20_ask_proxy_usdt=1149847, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=8726978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T06:15:03+00:00, last15m_closed_end=2026-10-25T06:15+00:00, prior8high=0.937000, depth_time=2026-10-25T06:15:21+00:00, book20_bid_proxy_usdt=1434788, book20_ask_proxy_usdt=1116117, funding_indicative=0.000003, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.63%, turnover=64661240. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
