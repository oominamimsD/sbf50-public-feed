# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T02:15:43Z**
- feed_generated_utc: 2026-10-18T02:15:45+00:00
- source_sha256: `7ab654f74b7bb0f54f884b13c244f73afa52de69a8ccb0431a8a4a36cc10d439`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T02:15+00:00, close=81630.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T02:00+00:00, close=81618.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.154100|-16.79|55.49|-17.17|14638544|6.48|
|SAND_USDT|0.059110|-6.23|-12.15|-6.61|27857732|1.69|
|TIA_USDT|0.631600|-4.01|23.11|-4.39|73148448|1.58|
|STRK_USDT|0.063820|-3.52|-31.69|-3.90|15560044|3.13|
|FILECOIN_USDT|1.057000|-2.79|-6.27|-3.17|19995909|0.95|
|EIGEN_USDT|0.249200|-2.77|5.77|-3.15|10736955|4.01|
|QNT_USDT|195.300000|-2.54|-20.32|-2.92|70003858|0.51|
|PUMPFUN_USDT|0.004314|-2.22|-24.64|-2.60|23539529|2.32|
|DNA_USDT|0.266300|-2.13|UNKNOWN|-2.51|5213066|7.51|
|XPL_USDT|0.078800|-1.65|-9.17|-2.03|5122355|1.27|
|ARB_USDT|0.181180|-1.48|-2.94|-1.86|31610829|0.55|
|OP_USDT|0.127370|-1.26|-8.06|-1.64|9662729|1.57|
|APT_USDT|0.789300|-1.02|-4.53|-1.40|10076161|1.27|
|WLD_USDT|0.490900|-0.94|-12.18|-1.32|65558728|2.04|
|PEPE_USDT|0.000004|-0.92|-4.49|-1.30|58601326|0.52|
|DOT_USDT|1.107800|-0.85|-11.86|-1.23|16547035|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.789300|0.790400|0.789300|1.37|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.181180|0.180450|0.181200|0.82|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.266300|0.256400|0.266300|2.55|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249200|0.248600|0.249200|0.11|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.057000|1.056900|1.057000|2.34|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.154100|0.153500|0.154100|0.36|N|Y/Y|N/N|Y|N|
|OP_USDT|0.127370|0.127540|0.127370|1.87|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000004|0.000004|0.000004|1.02|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004314|0.004314|0.004314|1.11|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.300000|194.070000|195.300000|0.78|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.059110|0.057980|0.059110|1.56|N|N/Y|N/N|Y|N|
|STRK_USDT|0.063820|0.063690|0.063690|1.21|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.631600|0.629300|0.631500|0.92|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.490900|0.487900|0.490800|0.49|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078800|0.078460|0.078790|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.800100, depth_time=2026-10-18T02:15:34+00:00, book20_bid_proxy_usdt=150997, book20_ask_proxy_usdt=159272, funding_indicative=-0.000071, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=10076161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.183400, depth_time=2026-10-18T02:15:32+00:00, book20_bid_proxy_usdt=71054, book20_ask_proxy_usdt=73332, funding_indicative=0.000015, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=31610829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.269200, depth_time=2026-10-18T02:15:27+00:00, book20_bid_proxy_usdt=70738, book20_ask_proxy_usdt=66769, funding_indicative=-0.002423, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=5213066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.253300, depth_time=2026-10-18T02:15:20+00:00, book20_bid_proxy_usdt=475835, book20_ask_proxy_usdt=333616, funding_indicative=-0.000012, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=10736955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=1.071500, depth_time=2026-10-18T02:15:17+00:00, book20_bid_proxy_usdt=323153, book20_ask_proxy_usdt=841368, funding_indicative=-0.000054, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=19995909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.173300, depth_time=2026-10-18T02:15:07+00:00, book20_bid_proxy_usdt=303526, book20_ask_proxy_usdt=180218, funding_indicative=-0.000055, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.79%, turnover=14638544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.129170, depth_time=2026-10-18T02:15:34+00:00, book20_bid_proxy_usdt=58411, book20_ask_proxy_usdt=105742, funding_indicative=-0.000127, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=9662729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.000004, depth_time=2026-10-18T02:15:42+00:00, book20_bid_proxy_usdt=92918, book20_ask_proxy_usdt=45773, funding_indicative=-0.000297, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=58601326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.004390, depth_time=2026-10-18T02:15:25+00:00, book20_bid_proxy_usdt=1233897, book20_ask_proxy_usdt=1605972, funding_indicative=0.000032, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=23539529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=198.820000, depth_time=2026-10-18T02:15:22+00:00, book20_bid_proxy_usdt=59124, book20_ask_proxy_usdt=93393, funding_indicative=-0.000115, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=70003858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.060420, depth_time=2026-10-18T02:15:10+00:00, book20_bid_proxy_usdt=566577, book20_ask_proxy_usdt=676462, funding_indicative=-0.003324, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.23%, turnover=27857732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.064520, depth_time=2026-10-18T02:15:14+00:00, book20_bid_proxy_usdt=271621, book20_ask_proxy_usdt=287596, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=15560044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.651200, depth_time=2026-10-18T02:15:12+00:00, book20_bid_proxy_usdt=216228, book20_ask_proxy_usdt=209153, funding_indicative=-0.000027, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=73148448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T02:15:02+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.496400, depth_time=2026-10-18T02:15:40+00:00, book20_bid_proxy_usdt=1457169, book20_ask_proxy_usdt=1552232, funding_indicative=-0.000137, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=65558728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T02:15:03+00:00, last15m_closed_end=2026-10-18T02:15+00:00, prior8high=0.079650, depth_time=2026-10-18T02:15:30+00:00, book20_bid_proxy_usdt=473320, book20_ask_proxy_usdt=483598, funding_indicative=0.000047, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=5122355. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
