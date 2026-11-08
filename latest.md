# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T05:45:25Z**
- feed_generated_utc: 2026-11-08T05:45:27+00:00
- source_sha256: `71e5e61e46ce0c993645ce94648f645fb4540e940b9d8bed6641b1eb758ecb50`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T05:45+00:00, close=75775.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T05:00+00:00, close=75830.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001962|-3.66|67.10|-3.72|26465289|0.51|
|ENA_USDT|0.154330|-2.43|-20.45|-2.49|28404759|0.65|
|TIA_USDT|0.432600|-2.03|-11.73|-2.09|7386660|2.31|
|WLD_USDT|0.330800|-1.43|-18.19|-1.49|23939837|3.02|
|ONDO_USDT|0.358100|-1.37|-13.16|-1.43|8829980|2.79|
|AAVE_USDT|130.480000|-1.32|-3.71|-1.38|10420721|0.77|
|QNT_USDT|196.680000|-1.09|-2.17|-1.15|46134302|0.51|
|LINK_USDT|10.740000|-0.95|-7.18|-1.01|68248198|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.480000|130.590000|130.480000|0.76|N|Y/N|N/N|Y|N|
|ENA_USDT|0.154330|0.153230|0.154330|0.65|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.740000|10.736000|10.740000|0.72|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358100|0.357400|0.358100|1.28|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001962|0.001804|0.001961|0.84|N|Y/Y|N/N|Y|N|
|QNT_USDT|196.680000|193.770000|196.680000|0.65|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.432600|0.432800|0.432600|0.63|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330800|0.329900|0.330800|1.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=132.130000, depth_time=2026-11-08T05:45:18+00:00, book20_bid_proxy_usdt=371624, book20_ask_proxy_usdt=978714, funding_indicative=-0.000002, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=10420721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=0.155100, depth_time=2026-11-08T05:45:09+00:00, book20_bid_proxy_usdt=240804, book20_ask_proxy_usdt=252555, funding_indicative=0.000044, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=28404759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=10.793000, depth_time=2026-11-08T05:45:24+00:00, book20_bid_proxy_usdt=1003761, book20_ask_proxy_usdt=526963, funding_indicative=0.000097, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=68248198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=0.361500, depth_time=2026-11-08T05:45:14+00:00, book20_bid_proxy_usdt=1954263, book20_ask_proxy_usdt=1548294, funding_indicative=0.000004, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=8829980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=0.001965, depth_time=2026-11-08T05:45:07+00:00, book20_bid_proxy_usdt=12422, book20_ask_proxy_usdt=11304, funding_indicative=0.000010, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=26465289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=195.930000, depth_time=2026-11-08T05:45:22+00:00, book20_bid_proxy_usdt=76914, book20_ask_proxy_usdt=82279, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=46134302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=0.438300, depth_time=2026-11-08T05:45:07+00:00, book20_bid_proxy_usdt=331248, book20_ask_proxy_usdt=331017, funding_indicative=0.000003, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=7386660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T05:44:59+00:00, last15m_closed_end=2026-11-08T05:45+00:00, prior8high=0.332600, depth_time=2026-11-08T05:45:13+00:00, book20_bid_proxy_usdt=3440694, book20_ask_proxy_usdt=4139800, funding_indicative=-0.000161, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=23939837. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
