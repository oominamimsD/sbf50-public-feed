# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T22:00:35Z**
- feed_generated_utc: 2026-11-07T22:00:37+00:00
- source_sha256: `293f4ad9bda74b80d70e2f7ddc10fd0b2bf892d0a8f08ecdd8bfe20b6222684f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T22:00+00:00, close=75715.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T22:00+00:00, close=75715.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.121900|-3.86|-60.76|-3.85|9455872|8.21|
|ENA_USDT|0.156900|-2.09|-19.12|-2.08|27079372|0.64|
|PUMPFUN_USDT|0.003671|-1.89|-12.21|-1.88|17089964|2.72|
|PEPE_USDT|0.000005|-1.85|-2.93|-1.84|41191339|0.21|
|WLD_USDT|0.331500|-1.45|-18.02|-1.44|25448046|3.02|
|QNT_USDT|196.440000|-1.34|-2.29|-1.33|40569184|0.51|
|AAVE_USDT|129.980000|-1.34|-4.08|-1.33|8689209|0.77|
|NEAR_USDT|3.656000|-1.26|-18.31|-1.25|23649195|2.73|
|ADA_USDT|0.180300|-1.25|-6.86|-1.24|12479773|5.54|
|LINK_USDT|10.776000|-1.18|-6.87|-1.17|71752848|0.93|
|DOT_USDT|0.889700|-1.18|-7.22|-1.17|5980468|1.12|
|SUI_USDT|0.851700|-1.05|-5.57|-1.04|22698246|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.980000|129.130000|129.980000|0.85|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.180300|0.179100|0.180300|0.33|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.889700|0.878700|0.889700|5.86|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.156900|0.155860|0.156900|0.47|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.776000|10.708000|10.776000|1.27|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.656000|3.620000|3.656000|0.87|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.64|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003671|0.003634|0.003671|0.35|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.440000|195.990000|196.440000|0.64|N|Y/N|N/N|Y|N|
|SUI_USDT|0.851700|0.846600|0.851700|1.64|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.121900|0.120300|0.121900|2.08|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.331500|0.327700|0.331500|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=131.400000, depth_time=2026-11-07T22:00:22+00:00, book20_bid_proxy_usdt=367606, book20_ask_proxy_usdt=851400, funding_indicative=0.000040, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=8689209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.181500, depth_time=2026-11-07T22:00:26+00:00, book20_bid_proxy_usdt=8959218, book20_ask_proxy_usdt=9872967, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=12479773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.899300, depth_time=2026-11-07T22:00:30+00:00, book20_bid_proxy_usdt=482510, book20_ask_proxy_usdt=497614, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=5980468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.157650, depth_time=2026-11-07T22:00:09+00:00, book20_bid_proxy_usdt=239241, book20_ask_proxy_usdt=237887, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=27079372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=10.841000, depth_time=2026-11-07T22:00:28+00:00, book20_bid_proxy_usdt=285274, book20_ask_proxy_usdt=557028, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=71752848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=3.659000, depth_time=2026-11-07T22:00:24+00:00, book20_bid_proxy_usdt=3898579, book20_ask_proxy_usdt=4645840, funding_indicative=0.000043, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=23649195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.000005, depth_time=2026-11-07T22:00:14+00:00, book20_bid_proxy_usdt=55596, book20_ask_proxy_usdt=44200, funding_indicative=0.000051, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=41191339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.003698, depth_time=2026-11-07T22:00:09+00:00, book20_bid_proxy_usdt=1834561, book20_ask_proxy_usdt=2541820, funding_indicative=0.000005, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=17089964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=198.600000, depth_time=2026-11-07T22:00:17+00:00, book20_bid_proxy_usdt=73178, book20_ask_proxy_usdt=54100, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=40569184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.859900, depth_time=2026-11-07T22:00:34+00:00, book20_bid_proxy_usdt=1809181, book20_ask_proxy_usdt=2064167, funding_indicative=0.000008, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=22698246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.124500, depth_time=2026-11-07T22:00:07+00:00, book20_bid_proxy_usdt=267043, book20_ask_proxy_usdt=207717, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=9455872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T22:00:01+00:00, last15m_closed_end=2026-11-07T22:00+00:00, prior8high=0.334300, depth_time=2026-11-07T22:00:17+00:00, book20_bid_proxy_usdt=4068022, book20_ask_proxy_usdt=3864377, funding_indicative=-0.000146, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=25448046. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
