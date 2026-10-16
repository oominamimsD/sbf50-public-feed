# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T19:30:42Z**
- feed_generated_utc: 2026-10-16T19:30:45+00:00
- source_sha256: `9b3f2c64bbd52aff3fce2b5546bc797a10e0a3c309b91b5f1864fcf7fd0d05e0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T19:30+00:00, close=81571.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T19:00+00:00, close=81114.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.196150|-4.33|61.22|-4.64|21579164|2.04|
|ZEC_USDT|1142.200000|-3.85|-6.25|-4.16|1517075844|0.09|
|RIVER_USDT|1.085000|-3.64|-8.20|-3.95|6125158|9.22|
|INJ_USDT|8.682000|-3.29|25.29|-3.60|115306419|1.15|
|ZRO_USDT|2.037800|-3.02|0.04|-3.33|15842795|0.98|
|PYTH_USDT|0.083980|-2.66|-1.65|-2.97|5503562|1.19|
|OP_USDT|0.136980|-2.15|11.16|-2.46|15318612|0.73|
|TAO_USDT|275.000000|-2.00|0.12|-2.31|82444971|1.09|
|STRK_USDT|0.072510|-1.94|-3.71|-2.25|25578495|1.38|
|HBAR_USDT|0.082510|-1.90|-9.18|-2.21|22582618|1.21|
|APT_USDT|0.840800|-1.78|5.03|-2.09|13136585|1.19|
|WLD_USDT|0.500700|-1.57|1.66|-1.88|94308583|2.00|
|DOT_USDT|1.156700|-1.20|-2.63|-1.51|22642170|0.86|
|ARB_USDT|0.192840|-1.07|6.65|-1.38|36552573|0.52|
|NEAR_USDT|4.998000|-0.95|5.19|-1.26|187345962|2.00|
|FARTCOIN_USDT|0.153370|-0.87|-6.12|-1.18|7545176|0.65|
|AVAX_USDT|10.000000|-0.82|-1.88|-1.13|125446323|1.00|
|FET_USDT|0.198100|-0.75|-8.70|-1.06|11574995|5.05|
|AAVE_USDT|156.110000|-0.74|-8.08|-1.05|32535538|1.28|
|ONDO_USDT|0.453700|-0.74|-5.49|-1.05|30701072|2.20|
|ATOM_USDT|1.727000|-0.74|-13.47|-1.05|7174969|5.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.840800|0.825100|0.840800|0.32|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192840|0.189190|0.192840|0.61|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.196150|0.192280|0.196150|0.44|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.156700|1.134400|1.156700|0.44|N|Y/N|N/N|Y|N|
|HBAR_USDT|0.082510|0.082050|0.082510|0.37|N|Y/Y|Y/N|Y|N|
|INJ_USDT|8.682000|8.521000|8.682000|0.86|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.998000|4.920000|4.998000|0.61|N|Y/Y|Y/N|Y|N|
|OP_USDT|0.136980|0.133270|0.136980|0.74|N|Y/Y|N/N|Y|N|
|PYTH_USDT|0.083980|0.083060|0.083980|0.66|N|Y/Y|Y/N|Y|N|
|RIVER_USDT|1.085000|1.066000|1.085000|0.13|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072510|0.071560|0.072510|0.25|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.000000|272.270000|274.940000|0.29|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.500700|0.492700|0.500500|0.64|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1142.200000|1133.160000|1142.110000|0.79|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.037800|1.975000|2.037800|0.29|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.853600, depth_time=2026-10-16T19:30:31+00:00, book20_bid_proxy_usdt=82649, book20_ask_proxy_usdt=105630, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=13136585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.195640, depth_time=2026-10-16T19:30:38+00:00, book20_bid_proxy_usdt=78895, book20_ask_proxy_usdt=33750, funding_indicative=0.000029, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=36552573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.199240, depth_time=2026-10-16T19:30:07+00:00, book20_bid_proxy_usdt=29771, book20_ask_proxy_usdt=23037, funding_indicative=-0.000172, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=21579164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=1.181200, depth_time=2026-10-16T19:30:36+00:00, book20_bid_proxy_usdt=214515, book20_ask_proxy_usdt=196219, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=22642170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.083300, depth_time=2026-10-16T19:30:28+00:00, book20_bid_proxy_usdt=689526, book20_ask_proxy_usdt=1098114, funding_indicative=0.000025, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=22582618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=8.853000, depth_time=2026-10-16T19:30:14+00:00, book20_bid_proxy_usdt=264092, book20_ask_proxy_usdt=246422, funding_indicative=0.000232, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=115306419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=5.147000, depth_time=2026-10-16T19:30:41+00:00, book20_bid_proxy_usdt=380000, book20_ask_proxy_usdt=704297, funding_indicative=0.000028, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=187345962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.138210, depth_time=2026-10-16T19:30:21+00:00, book20_bid_proxy_usdt=46630, book20_ask_proxy_usdt=64129, funding_indicative=0.000052, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=15318612. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.086180, depth_time=2026-10-16T19:30:18+00:00, book20_bid_proxy_usdt=136180, book20_ask_proxy_usdt=168024, funding_indicative=-0.000046, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=5503562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=1.129000, depth_time=2026-10-16T19:30:12+00:00, book20_bid_proxy_usdt=364882, book20_ask_proxy_usdt=322706, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=6125158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.073590, depth_time=2026-10-16T19:30:26+00:00, book20_bid_proxy_usdt=299946, book20_ask_proxy_usdt=328991, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=25578495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=279.920000, depth_time=2026-10-16T19:30:24+00:00, book20_bid_proxy_usdt=54669, book20_ask_proxy_usdt=78284, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=82444971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=0.508400, depth_time=2026-10-16T19:30:33+00:00, book20_bid_proxy_usdt=1842931, book20_ask_proxy_usdt=2125576, funding_indicative=0.000060, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=94308583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=1171.830000, depth_time=2026-10-16T19:30:09+00:00, book20_bid_proxy_usdt=553182, book20_ask_proxy_usdt=114897, funding_indicative=0.000081, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=1517075844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T19:30:00+00:00, last15m_closed_end=2026-10-16T19:30+00:00, prior8high=2.051400, depth_time=2026-10-16T19:30:16+00:00, book20_bid_proxy_usdt=36359, book20_ask_proxy_usdt=36194, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=15842795. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
