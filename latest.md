# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T20:00:30Z**
- feed_generated_utc: 2026-11-03T20:00:32+00:00
- source_sha256: `1423fcf04cf1567c1b0a0ce27512dfb4b0605d790baddc3ce669c7046d0e3e5e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003898|-5.13|-81.54|-5.41|13220461|7.70|
|TIA_USDT|0.430600|-2.11|-19.67|-2.39|11541000|2.32|
|TRUMPOFFICIAL_USDT|1.575000|-1.93|-6.69|-2.21|5859250|6.35|
|XPL_USDT|0.063130|-1.81|-14.48|-2.09|8905160|1.58|
|QNT_USDT|191.200000|-1.80|-3.38|-2.08|56257245|0.52|
|OP_USDT|0.109690|-1.34|-1.46|-1.62|8555710|0.91|
|HBAR_USDT|0.069330|-1.22|-8.92|-1.50|5452921|1.44|
|SILVER_USDT|49.560000|-1.21|-9.29|-1.49|355056286|2.02|
|LINK_USDT|11.053000|-1.05|-3.47|-1.33|154141697|1.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003898|0.003757|0.003898|0.46|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.069330|0.069250|0.069340|0.45|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.053000|11.053000|11.053000|0.93|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109690|0.109440|0.109690|1.60|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.200000|190.330000|191.180000|0.87|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.560000|49.640000|49.560000|1.83|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.430600|0.429100|0.430700|0.52|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.575000|1.574000|1.575000|1.46|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.063130|0.062920|0.063130|1.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=0.004045, depth_time=2026-11-03T20:00:08+00:00, book20_bid_proxy_usdt=53856, book20_ask_proxy_usdt=66391, funding_indicative=-0.000478, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=13220461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=0.069910, depth_time=2026-11-03T20:00:23+00:00, book20_bid_proxy_usdt=1359483, book20_ask_proxy_usdt=1076260, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=5452921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=11.185000, depth_time=2026-11-03T20:00:29+00:00, book20_bid_proxy_usdt=502886, book20_ask_proxy_usdt=810827, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=154141697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=0.110950, depth_time=2026-11-03T20:00:17+00:00, book20_bid_proxy_usdt=190535, book20_ask_proxy_usdt=153656, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=8555710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=195.440000, depth_time=2026-11-03T20:00:18+00:00, book20_bid_proxy_usdt=80884, book20_ask_proxy_usdt=82296, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=56257245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=49.910000, depth_time=2026-11-03T20:00:26+00:00, book20_bid_proxy_usdt=73057165, book20_ask_proxy_usdt=49473515, funding_indicative=0.000080, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=355056286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=0.433900, depth_time=2026-11-03T20:00:10+00:00, book20_bid_proxy_usdt=426841, book20_ask_proxy_usdt=431479, funding_indicative=-0.000057, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=11541000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=1.592000, depth_time=2026-11-03T20:00:10+00:00, book20_bid_proxy_usdt=1795338, book20_ask_proxy_usdt=2184749, funding_indicative=0.000040, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=5859250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T20:00:00+00:00, last15m_closed_end=2026-11-03T20:00+00:00, prior8high=0.064140, depth_time=2026-11-03T20:00:16+00:00, book20_bid_proxy_usdt=320040, book20_ask_proxy_usdt=522430, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=8905160. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
