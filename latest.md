# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T17:15:20Z**
- feed_generated_utc: 2026-11-05T17:15:21+00:00
- source_sha256: `683386365824c7fe92fd423139a24d69dbbe57d6037b38436c7431ecc01b987b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T17:15+00:00, close=76161, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T17:00+00:00, close=76361, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.407000|-4.93|16.61|-5.12|8832920|4.16|
|TRUMPOFFICIAL_USDT|1.124000|-3.68|-34.95|-3.87|32874771|8.88|
|LIT_USDT|3.263800|-1.90|0.21|-2.09|10445081|0.31|
|BCH_USDT|275.270000|-1.37|-4.51|-1.56|9502426|3.63|
|ENA_USDT|0.160730|-1.17|-24.86|-1.36|55612562|0.62|
|ETHFI_USDT|0.520200|-1.06|-23.44|-1.25|5217310|1.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|275.270000|277.590000|275.260000|1.61|Y|Y/Y|Y/N|Y|N|
|ENA_USDT|0.160730|0.160030|0.160590|1.21|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.520200|0.516400|0.520100|1.19|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.407000|2.429000|2.407000|1.24|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.263800|3.245900|3.263800|1.41|N|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.124000|1.150000|1.124000|1.85|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-05T17:15:02+00:00, last15m_closed_end=2026-11-05T17:15+00:00, prior8high=284.800000, depth_time=2026-11-05T17:15:14+00:00, book20_bid_proxy_usdt=57156, book20_ask_proxy_usdt=46330, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=9502426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T17:15:01+00:00, last15m_closed_end=2026-11-05T17:15+00:00, prior8high=0.173840, depth_time=2026-11-05T17:15:17+00:00, book20_bid_proxy_usdt=57073, book20_ask_proxy_usdt=188564, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=55612562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-11-05T17:15:02+00:00, last15m_closed_end=2026-11-05T17:15+00:00, prior8high=0.569400, depth_time=2026-11-05T17:15:19+00:00, book20_bid_proxy_usdt=201744, book20_ask_proxy_usdt=192250, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=5217310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T17:15:01+00:00, last15m_closed_end=2026-11-05T17:15+00:00, prior8high=2.611000, depth_time=2026-11-05T17:15:06+00:00, book20_bid_proxy_usdt=196218, book20_ask_proxy_usdt=222812, funding_indicative=0.000192, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=8832920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-05T17:15:02+00:00, last15m_closed_end=2026-11-05T17:15+00:00, prior8high=3.478900, depth_time=2026-11-05T17:15:11+00:00, book20_bid_proxy_usdt=20724, book20_ask_proxy_usdt=54700, funding_indicative=-0.000032, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=10445081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T17:15:02+00:00, last15m_closed_end=2026-11-05T17:15+00:00, prior8high=1.212000, depth_time=2026-11-05T17:15:09+00:00, book20_bid_proxy_usdt=1555974, book20_ask_proxy_usdt=1890980, funding_indicative=-0.000074, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=32874771. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
