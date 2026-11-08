# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T15:45:29Z**
- feed_generated_utc: 2026-11-08T15:45:30+00:00
- source_sha256: `fb3002f52ba094bbdf669ce1632eaa709313a253df8372f33bb24ce57d9a9999`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T15:45+00:00, close=76048.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T15:00+00:00, close=76006.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.031161|-6.41|77.84|-6.83|15306042|3.53|
|TIA_USDT|0.420800|-4.71|-14.13|-5.13|7139207|2.38|
|WLD_USDT|0.325800|-2.92|-19.43|-3.34|24807764|3.07|
|ONE_USDT|0.001982|-2.68|68.81|-3.10|22384592|0.50|
|ENA_USDT|0.154280|-2.46|-20.47|-2.88|24879561|0.65|
|AAVE_USDT|129.520000|-2.04|-4.42|-2.46|9465057|0.77|
|LINK_USDT|10.732000|-1.03|-7.25|-1.45|59824554|0.93|
|SUI_USDT|0.851000|-0.71|-5.65|-1.13|24859550|1.18|
|DOT_USDT|0.888500|-0.60|-7.35|-1.02|6519729|1.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.520000|128.470000|129.520000|0.41|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.888500|0.887600|0.888400|1.56|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154280|0.152750|0.154280|1.01|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.031161|0.029797|0.031161|0.92|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.732000|10.691000|10.732000|1.03|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001982|0.001818|0.001982|0.86|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.851000|0.845000|0.851000|0.26|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.420800|0.419200|0.420800|0.51|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.325800|0.323500|0.325800|1.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=130.520000, depth_time=2026-11-08T15:45:13+00:00, book20_bid_proxy_usdt=319773, book20_ask_proxy_usdt=432530, funding_indicative=0.000075, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=9465057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.896900, depth_time=2026-11-08T15:45:27+00:00, book20_bid_proxy_usdt=401545, book20_ask_proxy_usdt=662936, funding_indicative=-0.000103, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=6519729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.155430, depth_time=2026-11-08T15:45:18+00:00, book20_bid_proxy_usdt=324335, book20_ask_proxy_usdt=266175, funding_indicative=-0.000046, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=24879561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.031239, depth_time=2026-11-08T15:45:07+00:00, book20_bid_proxy_usdt=4373, book20_ask_proxy_usdt=5078, funding_indicative=0.000997, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=15306042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=10.754000, depth_time=2026-11-08T15:45:21+00:00, book20_bid_proxy_usdt=374811, book20_ask_proxy_usdt=408478, funding_indicative=0.000021, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=59824554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.001958, depth_time=2026-11-08T15:45:14+00:00, book20_bid_proxy_usdt=12016, book20_ask_proxy_usdt=17137, funding_indicative=-0.001413, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=22384592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.855500, depth_time=2026-11-08T15:45:24+00:00, book20_bid_proxy_usdt=1601314, book20_ask_proxy_usdt=1842681, funding_indicative=0.000051, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=24859550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.422800, depth_time=2026-11-08T15:45:04+00:00, book20_bid_proxy_usdt=226487, book20_ask_proxy_usdt=266896, funding_indicative=0.000006, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.71%, turnover=7139207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T15:45:00+00:00, last15m_closed_end=2026-11-08T15:45+00:00, prior8high=0.328300, depth_time=2026-11-08T15:45:12+00:00, book20_bid_proxy_usdt=3796238, book20_ask_proxy_usdt=3317247, funding_indicative=-0.000092, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=24807764. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
