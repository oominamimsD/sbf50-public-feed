# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T00:45:38Z**
- feed_generated_utc: 2026-10-23T00:45:40+00:00
- source_sha256: `33322447515c9d062c4fa51bf0827bfd80fe462dace4f264cefbd95571621949`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T00:45+00:00, close=81450, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.390600|-6.18|9.67|-5.94|13444716|0.29|
|STRK_USDT|0.052630|-3.18|-45.38|-2.94|13049109|1.90|
|XMR_USDT|596.710000|-2.64|9.69|-2.40|27370634|0.34|
|XPL_USDT|0.075750|-2.25|-10.60|-2.01|5725399|1.32|
|PUMPFUN_USDT|0.004575|-2.22|1.08|-1.98|37567603|2.19|
|TIA_USDT|0.556300|-2.12|-7.66|-1.88|23508137|1.80|
|APT_USDT|0.757800|-1.86|-8.33|-1.62|9058422|1.32|
|SEI_USDT|0.056990|-1.85|-7.27|-1.61|9956690|3.51|
|PHA_USDT|0.060900|-1.85|20.54|-1.61|8367285|4.93|
|ARB_USDT|0.180290|-1.82|-5.08|-1.58|32346738|0.56|
|OP_USDT|0.117660|-1.82|-15.27|-1.58|6808458|0.85|
|QNT_USDT|187.710000|-1.57|-9.71|-1.33|58701375|0.53|
|CRV_USDT|0.362700|-1.25|2.37|-1.01|5002368|2.76|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.757800|0.748700|0.757800|0.82|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.180290|0.177500|0.180310|0.24|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.362700|0.361400|0.362700|0.72|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.390600|3.363100|3.390600|0.70|N|Y/Y|Y/N|Y|N|
|OP_USDT|0.117660|0.117250|0.117660|1.08|N|Y/Y|Y/Y|Y|N|
|PHA_USDT|0.060900|0.060560|0.060900|0.64|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004575|0.004525|0.004575|1.67|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.710000|185.530000|187.710000|0.62|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.056990|0.056780|0.056980|0.86|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052630|0.052550|0.052630|1.42|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.556300|0.555400|0.556300|0.40|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|596.710000|593.340000|596.710000|1.72|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.075750|0.075130|0.075750|0.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.758100, depth_time=2026-10-23T00:45:22+00:00, book20_bid_proxy_usdt=156337, book20_ask_proxy_usdt=162077, funding_indicative=-0.000047, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=9058422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.180290, depth_time=2026-10-23T00:45:29+00:00, book20_bid_proxy_usdt=162306, book20_ask_proxy_usdt=50326, funding_indicative=-0.000119, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=32346738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-23T00:45:01+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.364100, depth_time=2026-10-23T00:45:35+00:00, book20_bid_proxy_usdt=392283, book20_ask_proxy_usdt=432197, funding_indicative=-0.000101, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=5002368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=3.453100, depth_time=2026-10-23T00:45:08+00:00, book20_bid_proxy_usdt=27015, book20_ask_proxy_usdt=25004, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.18%, turnover=13444716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.118330, depth_time=2026-10-23T00:45:32+00:00, book20_bid_proxy_usdt=91087, book20_ask_proxy_usdt=106292, funding_indicative=-0.000202, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=6808458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.061540, depth_time=2026-10-23T00:45:24+00:00, book20_bid_proxy_usdt=72276, book20_ask_proxy_usdt=61139, funding_indicative=-0.000566, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=8367285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.004612, depth_time=2026-10-23T00:45:17+00:00, book20_bid_proxy_usdt=1632461, book20_ask_proxy_usdt=1964400, funding_indicative=0.000022, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=37567603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=188.250000, depth_time=2026-10-23T00:45:35+00:00, book20_bid_proxy_usdt=68409, book20_ask_proxy_usdt=98017, funding_indicative=-0.000146, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=58701375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.057280, depth_time=2026-10-23T00:45:25+00:00, book20_bid_proxy_usdt=243347, book20_ask_proxy_usdt=262453, funding_indicative=-0.000022, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=9956690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.053350, depth_time=2026-10-23T00:45:10+00:00, book20_bid_proxy_usdt=488099, book20_ask_proxy_usdt=571582, funding_indicative=0.000032, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=13049109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.560500, depth_time=2026-10-23T00:45:19+00:00, book20_bid_proxy_usdt=369506, book20_ask_proxy_usdt=404437, funding_indicative=-0.000015, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=23508137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T00:45:00+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=602.780000, depth_time=2026-10-23T00:45:12+00:00, book20_bid_proxy_usdt=9012, book20_ask_proxy_usdt=97900, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=27370634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T00:45:01+00:00, last15m_closed_end=2026-10-23T00:45+00:00, prior8high=0.075880, depth_time=2026-10-23T00:45:15+00:00, book20_bid_proxy_usdt=426138, book20_ask_proxy_usdt=673926, funding_indicative=-0.000013, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=5725399. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
