# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T03:30:23Z**
- feed_generated_utc: 2026-10-21T03:30:26+00:00
- source_sha256: `cbc0eb9f76dc726038df0a15dfd80d431404b01e1ff5356bd36d5230330cd960`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T03:30+00:00, close=82758.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T03:00+00:00, close=82770, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186650|-13.49|5.22|-13.70|10483515|1.61|
|XMR_USDT|576.100000|-7.11|9.12|-7.32|20390760|0.17|
|BR_USDT|0.614130|-5.61|41.82|-5.82|35417150|0.98|
|Q_USDT|0.118302|-3.62|187.65|-3.83|5064274|8.71|
|TIA_USDT|0.609200|-2.16|5.52|-2.37|48655074|1.64|
|AGT_USDT|0.063357|-1.96|291.64|-2.17|6955234|5.20|
|SEI_USDT|0.061000|-1.02|-2.19|-1.23|6261926|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063357|0.061376|0.063357|0.82|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186650|0.185410|0.186650|0.31|N|Y/Y|N/N|N|N|
|BR_USDT|0.614130|0.614910|0.614130|1.04|N|Y/Y|N/N|N|N|
|Q_USDT|0.118302|0.116120|0.118302|1.13|N|Y/Y|N/N|N|N|
|SEI_USDT|0.061000|0.060850|0.061000|2.30|N|N/N|Y/Y|N|N|
|TIA_USDT|0.609200|0.608400|0.609200|0.44|N|Y/Y|Y/Y|N|N|
|XMR_USDT|576.100000|572.610000|575.790000|0.76|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=0.066377, depth_time=2026-10-21T03:30:19+00:00, book20_bid_proxy_usdt=7136, book20_ask_proxy_usdt=6609, funding_indicative=0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=6955234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=0.191790, depth_time=2026-10-21T03:30:08+00:00, book20_bid_proxy_usdt=19593, book20_ask_proxy_usdt=26100, funding_indicative=0.000055, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.49%, turnover=10483515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=0.663490, depth_time=2026-10-21T03:30:13+00:00, book20_bid_proxy_usdt=4422, book20_ask_proxy_usdt=2026, funding_indicative=-0.000015, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.61%, turnover=35417150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=0.123233, depth_time=2026-10-21T03:30:12+00:00, book20_bid_proxy_usdt=19058, book20_ask_proxy_usdt=17610, funding_indicative=-0.000145, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=5064274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=0.061880, depth_time=2026-10-21T03:30:21+00:00, book20_bid_proxy_usdt=332125, book20_ask_proxy_usdt=304241, funding_indicative=-0.000082, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=6261926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=0.619700, depth_time=2026-10-21T03:30:17+00:00, book20_bid_proxy_usdt=220443, book20_ask_proxy_usdt=235442, funding_indicative=-0.000054, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=48655074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T03:30:01+00:00, last15m_closed_end=2026-10-21T03:30+00:00, prior8high=601.630000, depth_time=2026-10-21T03:30:10+00:00, book20_bid_proxy_usdt=16314, book20_ask_proxy_usdt=13138, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.11%, turnover=20390760. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
