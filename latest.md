# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T13:15:36Z**
- feed_generated_utc: 2026-10-18T13:15:38+00:00
- source_sha256: `f85e694385206f4b32c60505194bf9fec10df285a8fe2f8f526062cf17b465c5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T13:15+00:00, close=81877.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T13:00+00:00, close=81952.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.238800|-6.82|1.35|-7.51|5852559|4.19|
|STRK_USDT|0.061680|-6.75|-33.98|-7.44|14426135|1.62|
|TIA_USDT|0.626500|-4.78|22.12|-5.47|59141812|1.60|
|ZRO_USDT|1.818100|-3.56|-10.02|-4.25|6206814|3.85|
|PUMPFUN_USDT|0.004255|-3.55|-25.67|-4.24|19239331|2.35|
|FILECOIN_USDT|1.054300|-3.04|-6.51|-3.73|17232746|0.95|
|XPL_USDT|0.078050|-2.59|-10.03|-3.28|5516029|1.28|
|INJ_USDT|8.274000|-2.22|13.43|-2.91|39168694|1.21|
|OP_USDT|0.126220|-2.15|-8.89|-2.84|8360540|0.79|
|ZEC_USDT|1119.850000|-1.88|-9.08|-2.57|1203639592|0.18|
|DOT_USDT|1.098400|-1.70|-12.61|-2.39|15722567|0.91|
|ICP_USDT|2.897000|-1.05|-8.00|-1.74|5683036|3.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.098400|1.102600|1.098400|1.83|Y|Y/Y|Y/Y|N|Y|
|EIGEN_USDT|0.238800|0.239100|0.238800|1.37|Y|Y/Y|Y/Y|N|Y|
|FILECOIN_USDT|1.054300|1.053700|1.054300|0.98|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.897000|2.889000|2.897000|3.83|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.274000|8.276000|8.272000|3.67|Y|Y/Y|Y/N|N|N|
|OP_USDT|0.126220|0.125830|0.126240|2.08|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004255|0.004254|0.004254|9.02|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.061680|0.061150|0.061680|1.01|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.626500|0.627600|0.626500|1.91|Y|Y/Y|N/Y|N|N|
|XPL_USDT|0.078050|0.078080|0.078050|2.10|Y|Y/Y|Y/Y|N|Y|
|ZEC_USDT|1119.850000|1123.060000|1119.830000|1.49|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.818100|1.822800|1.818100|8.91|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=1.112100, depth_time=2026-10-18T13:15:33+00:00, book20_bid_proxy_usdt=279270, book20_ask_proxy_usdt=382878, funding_indicative=-0.000021, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=15722567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=0.244000, depth_time=2026-10-18T13:15:06+00:00, book20_bid_proxy_usdt=597517, book20_ask_proxy_usdt=561669, funding_indicative=0.000015, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.82%, turnover=5852559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=1.064600, depth_time=2026-10-18T13:15:20+00:00, book20_bid_proxy_usdt=570570, book20_ask_proxy_usdt=730884, funding_indicative=0.000023, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=17232746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T13:15:02+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=2.914000, depth_time=2026-10-18T13:15:35+00:00, book20_bid_proxy_usdt=921103, book20_ask_proxy_usdt=980641, funding_indicative=0.000065, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=5683036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=8.489000, depth_time=2026-10-18T13:15:26+00:00, book20_bid_proxy_usdt=268444, book20_ask_proxy_usdt=341961, funding_indicative=-0.000121, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=39168694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=0.127610, depth_time=2026-10-18T13:15:27+00:00, book20_bid_proxy_usdt=52940, book20_ask_proxy_usdt=85698, funding_indicative=-0.000180, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=8360540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=0.004313, depth_time=2026-10-18T13:15:19+00:00, book20_bid_proxy_usdt=2180789, book20_ask_proxy_usdt=1794322, funding_indicative=0.000015, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=19239331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=0.062550, depth_time=2026-10-18T13:15:11+00:00, book20_bid_proxy_usdt=405633, book20_ask_proxy_usdt=372972, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.75%, turnover=14426135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=0.658000, depth_time=2026-10-18T13:15:14+00:00, book20_bid_proxy_usdt=154102, book20_ask_proxy_usdt=216559, funding_indicative=-0.000061, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=59141812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T13:15:02+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=0.078830, depth_time=2026-10-18T13:15:23+00:00, book20_bid_proxy_usdt=404871, book20_ask_proxy_usdt=446074, funding_indicative=0.000043, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=5516029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T13:15:01+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=1135.430000, depth_time=2026-10-18T13:15:31+00:00, book20_bid_proxy_usdt=791845, book20_ask_proxy_usdt=428158, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=1203639592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T13:15:02+00:00, last15m_closed_end=2026-10-18T13:15+00:00, prior8high=1.851100, depth_time=2026-10-18T13:15:16+00:00, book20_bid_proxy_usdt=42261, book20_ask_proxy_usdt=66292, funding_indicative=-0.000011, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=6206814. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
