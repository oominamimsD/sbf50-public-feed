# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T11:00:27Z**
- feed_generated_utc: 2026-10-21T11:00:30+00:00
- source_sha256: `1d7c6488d5d66b6b92591ad0eb7490c726bbbd7a60f115aec1c2e39c1c0d09a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T11:00+00:00, close=83362.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T11:00+00:00, close=83362.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.046455|-27.04|187.16|-27.98|6540703|2.36|
|BAT_USDT|0.182370|-16.49|2.81|-17.43|10539568|0.55|
|BR_USDT|0.580660|-10.75|34.09|-11.69|22824726|0.17|
|BTW_USDT|1.757500|-4.18|-9.98|-5.12|24709023|3.99|
|TIA_USDT|0.620100|-3.24|7.41|-4.18|46433080|1.61|
|Q_USDT|0.118880|-3.15|189.05|-4.09|5308142|2.78|
|DOT_USDT|1.152500|-2.66|-0.38|-3.60|14676811|0.87|
|STRK_USDT|0.055910|-2.61|-35.68|-3.55|17947900|1.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.046455|0.043233|0.046455|0.76|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.182370|0.181440|0.182370|0.40|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.580660|0.566870|0.580950|0.75|N|Y/Y|N/N|N|N|
|BTW_USDT|1.757500|1.665600|1.757500|1.58|N|Y/N|N/N|N|N|
|DOT_USDT|1.152500|1.140800|1.152500|1.68|N|Y/Y|N/N|N|N|
|Q_USDT|0.118880|0.117302|0.118838|0.90|N|Y/Y|N/N|N|N|
|STRK_USDT|0.055910|0.055040|0.055900|0.94|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.620100|0.614700|0.619800|0.90|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=0.051865, depth_time=2026-10-21T11:00:09+00:00, book20_bid_proxy_usdt=11120, book20_ask_proxy_usdt=11202, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-27.04%, turnover=6540703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=0.185510, depth_time=2026-10-21T11:00:12+00:00, book20_bid_proxy_usdt=26347, book20_ask_proxy_usdt=24686, funding_indicative=-0.000128, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.49%, turnover=10539568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=0.608980, depth_time=2026-10-21T11:00:15+00:00, book20_bid_proxy_usdt=2572, book20_ask_proxy_usdt=3096, funding_indicative=-0.000086, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.75%, turnover=22824726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=2.142600, depth_time=2026-10-21T11:00:17+00:00, book20_bid_proxy_usdt=6996, book20_ask_proxy_usdt=8055, funding_indicative=-0.002395, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.18%, turnover=24709023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T11:00:04+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=1.162400, depth_time=2026-10-21T11:00:24+00:00, book20_bid_proxy_usdt=304955, book20_ask_proxy_usdt=319854, funding_indicative=-0.000263, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=14676811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=0.124375, depth_time=2026-10-21T11:00:22+00:00, book20_bid_proxy_usdt=15718, book20_ask_proxy_usdt=14915, funding_indicative=0.000021, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=5308142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=0.056790, depth_time=2026-10-21T11:00:27+00:00, book20_bid_proxy_usdt=717317, book20_ask_proxy_usdt=606823, funding_indicative=0.000001, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=17947900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T11:00:03+00:00, last15m_closed_end=2026-10-21T11:00+00:00, prior8high=0.632300, depth_time=2026-10-21T11:00:19+00:00, book20_bid_proxy_usdt=224391, book20_ask_proxy_usdt=308003, funding_indicative=-0.000085, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=46433080. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
