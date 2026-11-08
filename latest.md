# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T08:00:32Z**
- feed_generated_utc: 2026-11-08T08:00:34+00:00
- source_sha256: `7114d76cc7a522928790d3fcc1600ca2277e03f6a213648c030ddf5c138dd109`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005453|-8.85|-51.04|-9.13|38066500|5.50|
|TIA_USDT|0.430700|-2.46|-12.11|-2.74|7820961|2.32|
|ENA_USDT|0.154480|-2.33|-20.37|-2.61|29393528|0.65|
|WLD_USDT|0.330100|-1.63|-18.37|-1.91|24102782|3.03|
|QNT_USDT|195.660000|-1.60|-2.68|-1.88|45804853|0.51|
|ONE_USDT|0.002004|-1.60|70.68|-1.88|26372353|0.50|
|AAVE_USDT|130.540000|-1.27|-3.66|-1.55|10805077|0.77|
|LINK_USDT|10.745000|-0.91|-7.13|-1.19|67597505|0.93|
|ONDO_USDT|0.359900|-0.88|-12.73|-1.16|8716985|2.78|
|ADA_USDT|0.180200|-0.77|-6.92|-1.05|9831639|5.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.540000|129.910000|130.540000|1.25|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180200|0.179600|0.180200|2.14|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005453|0.005067|0.005452|2.71|N|N/Y|N/N|Y|N|
|ENA_USDT|0.154480|0.153450|0.154480|0.27|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.745000|10.711000|10.745000|0.85|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359900|0.357600|0.359900|2.83|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.002004|0.001905|0.002004|0.64|N|N/Y|N/N|Y|N|
|QNT_USDT|195.660000|194.160000|195.660000|0.49|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.430700|0.429800|0.430700|0.63|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.330100|0.328600|0.330100|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=131.110000, depth_time=2026-11-08T08:00:21+00:00, book20_bid_proxy_usdt=361272, book20_ask_proxy_usdt=309713, funding_indicative=0.000023, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=10805077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.180400, depth_time=2026-11-08T08:00:32+00:00, book20_bid_proxy_usdt=11175673, book20_ask_proxy_usdt=8599315, funding_indicative=0.000010, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=9831639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T07:59:58+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.005232, depth_time=2026-11-08T08:00:07+00:00, book20_bid_proxy_usdt=54354, book20_ask_proxy_usdt=44038, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.85%, turnover=38066500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.155160, depth_time=2026-11-08T08:00:12+00:00, book20_bid_proxy_usdt=295246, book20_ask_proxy_usdt=253570, funding_indicative=0.000042, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=29393528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=10.761000, depth_time=2026-11-08T08:00:25+00:00, book20_bid_proxy_usdt=393530, book20_ask_proxy_usdt=432970, funding_indicative=0.000079, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=67597505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.359900, depth_time=2026-11-08T08:00:29+00:00, book20_bid_proxy_usdt=1855287, book20_ask_proxy_usdt=1073771, funding_indicative=0.000000, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=8716985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T07:59:58+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.002049, depth_time=2026-11-08T08:00:21+00:00, book20_bid_proxy_usdt=24237, book20_ask_proxy_usdt=12881, funding_indicative=-0.000583, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=26372353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=196.680000, depth_time=2026-11-08T08:00:18+00:00, book20_bid_proxy_usdt=75709, book20_ask_proxy_usdt=59214, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=45804853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T07:59:58+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.434500, depth_time=2026-11-08T08:00:03+00:00, book20_bid_proxy_usdt=286720, book20_ask_proxy_usdt=303898, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=7820961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T07:59:59+00:00, last15m_closed_end=2026-11-08T08:00+00:00, prior8high=0.331300, depth_time=2026-11-08T08:00:15+00:00, book20_bid_proxy_usdt=3725575, book20_ask_proxy_usdt=3015614, funding_indicative=-0.000159, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=24102782. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
