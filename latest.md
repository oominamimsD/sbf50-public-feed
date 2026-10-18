# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T00:45:39Z**
- feed_generated_utc: 2026-10-18T00:45:41+00:00
- source_sha256: `2db3754ead268f904944362de629c47351cc25724d5fd6fcb47756d20e9c5beb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T00:45+00:00, close=81458.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.165600|-10.58|67.10|-10.75|14807164|6.04|
|SAND_USDT|0.058490|-7.21|-13.07|-7.38|27034447|1.71|
|STRK_USDT|0.063880|-3.43|-31.62|-3.60|16220033|1.56|
|QNT_USDT|194.440000|-2.97|-20.67|-3.14|67113960|0.51|
|EIGEN_USDT|0.249800|-2.53|6.02|-2.70|10802551|4.00|
|FILECOIN_USDT|1.060300|-2.49|-5.98|-2.66|20902363|0.94|
|TIA_USDT|0.644300|-2.08|25.59|-2.25|74183348|1.55|
|PUMPFUN_USDT|0.004327|-1.92|-24.41|-2.09|24703032|2.31|
|XPL_USDT|0.078650|-1.84|-9.34|-2.01|5112371|1.27|
|ZEC_USDT|1121.930000|-1.69|-8.91|-1.86|1163132298|0.09|
|ARB_USDT|0.180820|-1.68|-3.13|-1.85|30705922|0.55|
|DNA_USDT|0.268200|-1.43|UNKNOWN|-1.60|5532851|3.73|
|WLD_USDT|0.489300|-1.27|-12.46|-1.44|66455656|2.04|
|DOT_USDT|1.106000|-1.02|-12.00|-1.19|16993936|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180820|0.179600|0.180820|0.32|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.268200|0.254500|0.268200|1.31|N|Y/Y|?|Y|N|
|DOT_USDT|1.106000|1.100800|1.106000|0.42|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.249800|0.247800|0.249700|0.21|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.060300|1.050300|1.060300|0.90|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.165600|0.163200|0.165600|0.54|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004327|0.004297|0.004326|0.20|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.440000|193.740000|194.440000|0.17|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058490|0.058660|0.058490|0.70|N|N/N|N/N|Y|N|
|STRK_USDT|0.063880|0.063940|0.063870|0.39|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.644300|0.639600|0.644200|0.57|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.489300|0.484300|0.489300|0.90|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078650|0.078200|0.078640|0.21|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1121.930000|1113.720000|1122.190000|0.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.181720, depth_time=2026-10-18T00:45:31+00:00, book20_bid_proxy_usdt=49550, book20_ask_proxy_usdt=66342, funding_indicative=0.000043, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=30705922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.263000, depth_time=2026-10-18T00:45:33+00:00, book20_bid_proxy_usdt=104090, book20_ask_proxy_usdt=86084, funding_indicative=-0.001876, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=5532851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=1.117400, depth_time=2026-10-18T00:45:38+00:00, book20_bid_proxy_usdt=337416, book20_ask_proxy_usdt=310608, funding_indicative=-0.000023, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=16993936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.252000, depth_time=2026-10-18T00:45:17+00:00, book20_bid_proxy_usdt=398410, book20_ask_proxy_usdt=420710, funding_indicative=0.000015, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=10802551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=1.066900, depth_time=2026-10-18T00:45:19+00:00, book20_bid_proxy_usdt=661416, book20_ask_proxy_usdt=680004, funding_indicative=-0.000033, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=20902363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.174200, depth_time=2026-10-18T00:45:08+00:00, book20_bid_proxy_usdt=432293, book20_ask_proxy_usdt=206308, funding_indicative=-0.000097, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.58%, turnover=14807164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.004372, depth_time=2026-10-18T00:45:22+00:00, book20_bid_proxy_usdt=2053136, book20_ask_proxy_usdt=1512874, funding_indicative=0.000028, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=24703032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=196.940000, depth_time=2026-10-18T00:45:15+00:00, book20_bid_proxy_usdt=63733, book20_ask_proxy_usdt=87177, funding_indicative=-0.000062, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=67113960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.060240, depth_time=2026-10-18T00:45:10+00:00, book20_bid_proxy_usdt=294264, book20_ask_proxy_usdt=553023, funding_indicative=-0.002644, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.21%, turnover=27034447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.065060, depth_time=2026-10-18T00:45:12+00:00, book20_bid_proxy_usdt=426006, book20_ask_proxy_usdt=461010, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=16220033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.651200, depth_time=2026-10-18T00:45:22+00:00, book20_bid_proxy_usdt=212039, book20_ask_proxy_usdt=195217, funding_indicative=0.000005, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=74183348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.492900, depth_time=2026-10-18T00:45:36+00:00, book20_bid_proxy_usdt=1726811, book20_ask_proxy_usdt=1649451, funding_indicative=-0.000108, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=66455656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T00:45:02+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=0.078960, depth_time=2026-10-18T00:45:26+00:00, book20_bid_proxy_usdt=278237, book20_ask_proxy_usdt=477548, funding_indicative=0.000038, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=5112371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T00:45:01+00:00, last15m_closed_end=2026-10-18T00:45+00:00, prior8high=1131.290000, depth_time=2026-10-18T00:45:29+00:00, book20_bid_proxy_usdt=374389, book20_ask_proxy_usdt=295307, funding_indicative=0.000055, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=1163132298. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
