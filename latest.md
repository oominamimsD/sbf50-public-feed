# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T07:15:27Z**
- feed_generated_utc: 2026-11-08T07:15:28+00:00
- source_sha256: `c25f6487ac75937dfbf1e7d06ddb2dd36bbd2bb394210fe51d030e1987634a19`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T07:15+00:00, close=75833.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T07:00+00:00, close=75801.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005171|-13.57|-53.57|-13.71|37668949|3.87|
|TIA_USDT|0.431200|-2.35|-12.01|-2.49|7706686|2.32|
|ENA_USDT|0.154500|-2.32|-20.36|-2.46|29123367|0.65|
|ONE_USDT|0.001997|-1.94|70.08|-2.08|26041518|0.50|
|QNT_USDT|195.080000|-1.89|-2.96|-2.03|45454115|0.51|
|WLD_USDT|0.330500|-1.51|-18.27|-1.65|23295007|3.02|
|AAVE_USDT|130.550000|-1.27|-3.66|-1.41|10660687|0.77|
|ONDO_USDT|0.359300|-1.04|-12.87|-1.18|8580953|2.78|
|LINK_USDT|10.733000|-1.02|-7.24|-1.16|66708872|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.550000|129.910000|130.550000|0.86|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.005171|0.005067|0.005171|1.09|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.154500|0.153450|0.154500|1.43|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.733000|10.711000|10.733000|0.41|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359300|0.357600|0.359500|0.75|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001997|0.001864|0.001997|0.67|N|N/Y|N/N|Y|N|
|QNT_USDT|195.080000|194.160000|195.080000|0.66|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.431200|0.429800|0.431200|0.96|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330500|0.328600|0.330500|1.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=131.110000, depth_time=2026-11-08T07:15:19+00:00, book20_bid_proxy_usdt=349878, book20_ask_proxy_usdt=667402, funding_indicative=0.000018, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=10660687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=0.005418, depth_time=2026-11-08T07:15:07+00:00, book20_bid_proxy_usdt=63716, book20_ask_proxy_usdt=49912, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.57%, turnover=37668949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=0.155160, depth_time=2026-11-08T07:15:09+00:00, book20_bid_proxy_usdt=178248, book20_ask_proxy_usdt=293895, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=29123367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=10.771000, depth_time=2026-11-08T07:15:25+00:00, book20_bid_proxy_usdt=372478, book20_ask_proxy_usdt=510791, funding_indicative=0.000066, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=66708872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=0.359500, depth_time=2026-11-08T07:15:22+00:00, book20_bid_proxy_usdt=1680438, book20_ask_proxy_usdt=1521222, funding_indicative=-0.000025, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=8580953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=0.002049, depth_time=2026-11-08T07:15:14+00:00, book20_bid_proxy_usdt=11227, book20_ask_proxy_usdt=8141, funding_indicative=-0.000496, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=26041518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=196.790000, depth_time=2026-11-08T07:15:14+00:00, book20_bid_proxy_usdt=108038, book20_ask_proxy_usdt=63452, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=45454115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=0.435000, depth_time=2026-11-08T07:15:08+00:00, book20_bid_proxy_usdt=344391, book20_ask_proxy_usdt=406069, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=7706686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T07:14:59+00:00, last15m_closed_end=2026-11-08T07:15+00:00, prior8high=0.332600, depth_time=2026-11-08T07:15:18+00:00, book20_bid_proxy_usdt=4003782, book20_ask_proxy_usdt=3497060, funding_indicative=-0.000162, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=23295007. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
