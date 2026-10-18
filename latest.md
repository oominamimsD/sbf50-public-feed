# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T02:00:41Z**
- feed_generated_utc: 2026-10-18T02:00:43+00:00
- source_sha256: `8aa0d82df090b9fbf76322e5710667502319d71bd08999d01477ea4d7032a3a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T02:00+00:00, close=81618.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T02:00+00:00, close=81618.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.156300|-15.60|57.71|-15.97|14901974|6.40|
|TIA_USDT|0.633000|-3.79|23.39|-4.16|73665688|3.16|
|STRK_USDT|0.063800|-3.55|-31.71|-3.92|15865765|1.57|
|DNA_USDT|0.264200|-2.90|UNKNOWN|-3.27|5371050|7.57|
|FILECOIN_USDT|1.058100|-2.69|-6.18|-3.06|20418405|1.89|
|EIGEN_USDT|0.249900|-2.49|6.06|-2.86|10803627|4.00|
|QNT_USDT|196.220000|-2.09|-19.95|-2.46|70454711|2.55|
|PUMPFUN_USDT|0.004341|-1.60|-24.17|-1.97|23885283|2.30|
|XPL_USDT|0.079010|-1.39|-8.93|-1.76|5207286|1.26|
|ARB_USDT|0.181530|-1.29|-2.75|-1.66|32129010|0.55|
|WLD_USDT|0.490500|-1.02|-12.25|-1.39|66556192|2.04|
|OP_USDT|0.127710|-1.00|-7.82|-1.37|9820569|1.57|
|DOT_USDT|1.108300|-0.81|-11.82|-1.18|16773962|0.90|
|PEPE_USDT|0.000004|-0.69|-4.27|-1.06|59571085|0.26|
|APT_USDT|0.792000|-0.68|-4.20|-1.05|10208119|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.792000|0.790400|0.792000|3.41|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.181530|0.180450|0.181630|1.18|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.264200|0.256400|0.264200|0.49|N|Y/Y|?|Y|N|
|DOT_USDT|1.108300|1.105300|1.108300|0.80|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.249900|0.248600|0.249900|0.06|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.058100|1.058300|1.058100|3.67|Y|Y/Y|Y/Y|Y|Y|
|ICNT_USDT|0.156300|0.155400|0.156300|0.91|N|Y/Y|N/N|Y|N|
|OP_USDT|0.127710|0.127920|0.127690|1.22|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.96|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004341|0.004314|0.004341|0.91|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.220000|194.070000|196.200000|1.09|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063800|0.063700|0.063800|0.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.633000|0.630700|0.633000|1.60|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.490500|0.487900|0.490500|0.63|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.079010|0.078460|0.079010|0.40|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.799600, depth_time=2026-10-18T02:00:40+00:00, book20_bid_proxy_usdt=111094, book20_ask_proxy_usdt=123602, funding_indicative=-0.000060, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=10208119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.183000, depth_time=2026-10-18T02:00:28+00:00, book20_bid_proxy_usdt=58922, book20_ask_proxy_usdt=64440, funding_indicative=0.000024, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=32129010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.269200, depth_time=2026-10-18T02:00:13+00:00, book20_bid_proxy_usdt=82279, book20_ask_proxy_usdt=72492, funding_indicative=-0.002344, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=5371050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=1.117400, depth_time=2026-10-18T02:00:34+00:00, book20_bid_proxy_usdt=275510, book20_ask_proxy_usdt=260641, funding_indicative=0.000057, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=16773962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.253300, depth_time=2026-10-18T02:00:19+00:00, book20_bid_proxy_usdt=357333, book20_ask_proxy_usdt=387097, funding_indicative=-0.000019, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=10803627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=1.070300, depth_time=2026-10-18T02:00:17+00:00, book20_bid_proxy_usdt=427937, book20_ask_proxy_usdt=550079, funding_indicative=-0.000044, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=20418405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.173300, depth_time=2026-10-18T02:00:06+00:00, book20_bid_proxy_usdt=456203, book20_ask_proxy_usdt=163794, funding_indicative=0.000002, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.60%, turnover=14901974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.129510, depth_time=2026-10-18T02:00:33+00:00, book20_bid_proxy_usdt=57846, book20_ask_proxy_usdt=81846, funding_indicative=-0.000110, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=9820569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.000004, depth_time=2026-10-18T02:00:38+00:00, book20_bid_proxy_usdt=130254, book20_ask_proxy_usdt=42783, funding_indicative=-0.000281, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.69%, turnover=59571085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.004388, depth_time=2026-10-18T02:00:24+00:00, book20_bid_proxy_usdt=2210215, book20_ask_proxy_usdt=1415437, funding_indicative=0.000035, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=23885283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=198.820000, depth_time=2026-10-18T02:00:21+00:00, book20_bid_proxy_usdt=90736, book20_ask_proxy_usdt=90594, funding_indicative=-0.000102, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=70454711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.064770, depth_time=2026-10-18T02:00:12+00:00, book20_bid_proxy_usdt=236608, book20_ask_proxy_usdt=390287, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=15865765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.651200, depth_time=2026-10-18T02:00:10+00:00, book20_bid_proxy_usdt=122779, book20_ask_proxy_usdt=292062, funding_indicative=-0.000015, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=73665688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T01:59:58+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.496400, depth_time=2026-10-18T02:00:31+00:00, book20_bid_proxy_usdt=1917380, book20_ask_proxy_usdt=1679074, funding_indicative=-0.000117, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=66556192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T01:59:59+00:00, last15m_closed_end=2026-10-18T02:00+00:00, prior8high=0.079650, depth_time=2026-10-18T02:00:26+00:00, book20_bid_proxy_usdt=436587, book20_ask_proxy_usdt=386335, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=5207286. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
