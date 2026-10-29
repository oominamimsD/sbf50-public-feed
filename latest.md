# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T18:30:42Z**
- feed_generated_utc: 2026-10-29T18:30:44+00:00
- source_sha256: `bd00e1059b496eaad1c45507da70b1b3f90ef7b3001038df9720e50fb4f7ca5b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T18:30+00:00, close=80741, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T18:00+00:00, close=80857.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.498600|-8.51|-16.27|-7.30|9740396|0.67|
|Q_USDT|0.036740|-4.34|-71.48|-3.13|26753510|5.45|
|APT_USDT|0.672900|-4.32|-12.85|-3.11|9615238|1.49|
|PENGU_USDT|0.007781|-4.30|0.68|-3.09|6879882|1.28|
|NEAR_USDT|4.457000|-4.12|-9.85|-2.91|116694764|2.24|
|QNT_USDT|190.810000|-3.99|0.05|-2.78|64655470|0.52|
|WLD_USDT|0.419800|-3.78|-21.10|-2.57|84643171|2.38|
|FET_USDT|0.178100|-3.62|-3.88|-2.41|9646080|5.62|
|TRUMPOFFICIAL_USDT|1.667000|-3.53|-4.41|-2.32|6684487|6.00|
|FARTCOIN_USDT|0.129710|-3.48|-9.19|-2.27|11346992|0.77|
|ARB_USDT|0.168630|-3.34|-8.17|-2.13|29517213|1.19|
|OP_USDT|0.110240|-3.22|-8.01|-2.01|7031309|2.72|
|SEI_USDT|0.051750|-3.16|-10.88|-1.95|5749878|1.93|
|DOT_USDT|0.985600|-3.12|-12.33|-1.91|11171107|1.01|
|HBAR_USDT|0.073160|-2.80|-8.67|-1.59|15172478|1.37|
|ICP_USDT|2.558000|-2.62|-6.88|-1.41|5489248|3.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.672900|0.672400|0.672900|2.05|N|Y/N|N/Y|N|N|
|ARB_USDT|0.168630|0.168190|0.168630|0.37|N|N/N|N/Y|N|N|
|BTW_USDT|1.498600|1.509900|1.498600|0.70|N|Y/Y|Y/N|N|N|
|DOT_USDT|0.985600|0.985600|0.985600|0.61|N|Y/N|N/Y|N|N|
|FARTCOIN_USDT|0.129710|0.129390|0.129710|1.04|N|Y/N|N/Y|N|N|
|FET_USDT|0.178100|0.178600|0.178100|1.16|N|Y/N|N/N|N|N|
|HBAR_USDT|0.073160|0.073260|0.073160|1.59|Y|Y/N|Y/Y|N|N|
|NEAR_USDT|4.457000|4.452000|4.457000|0.30|N|Y/N|N/Y|N|N|
|OP_USDT|0.110240|0.110140|0.110240|0.25|N|N/N|N/Y|N|N|
|PENGU_USDT|0.007781|0.007806|0.007781|1.22|N|N/N|N/N|N|N|
|QNT_USDT|190.810000|190.720000|190.830000|0.94|N|Y/N|N/Y|N|N|
|Q_USDT|0.036740|0.037750|0.036720|3.09|Y|Y/Y|Y/Y|N|Y|
|SEI_USDT|0.051750|0.051850|0.051770|0.38|N|Y/N|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.667000|1.667000|1.667000|0.52|N|Y/N|N/Y|N|N|
|WLD_USDT|0.419800|0.418500|0.419800|0.39|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.701800, depth_time=2026-10-29T18:30:12+00:00, book20_bid_proxy_usdt=114997, book20_ask_proxy_usdt=244020, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=9615238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.174430, depth_time=2026-10-29T18:30:31+00:00, book20_bid_proxy_usdt=54200, book20_ask_proxy_usdt=103110, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=29517213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=1.625000, depth_time=2026-10-29T18:30:06+00:00, book20_bid_proxy_usdt=13039, book20_ask_proxy_usdt=30169, funding_indicative=-0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.51%, turnover=9740396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=1.014400, depth_time=2026-10-29T18:30:39+00:00, book20_bid_proxy_usdt=566678, book20_ask_proxy_usdt=542342, funding_indicative=0.000075, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=11171107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.134940, depth_time=2026-10-29T18:30:29+00:00, book20_bid_proxy_usdt=57761, book20_ask_proxy_usdt=102166, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=11346992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.184100, depth_time=2026-10-29T18:30:23+00:00, book20_bid_proxy_usdt=1602197, book20_ask_proxy_usdt=915777, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.62%, turnover=9646080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.075380, depth_time=2026-10-29T18:30:41+00:00, book20_bid_proxy_usdt=1092915, book20_ask_proxy_usdt=1010253, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=15172478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=4.648000, depth_time=2026-10-29T18:30:16+00:00, book20_bid_proxy_usdt=4395601, book20_ask_proxy_usdt=3192288, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.12%, turnover=116694764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.114180, depth_time=2026-10-29T18:30:33+00:00, book20_bid_proxy_usdt=115468, book20_ask_proxy_usdt=173718, funding_indicative=0.000046, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=7031309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.008088, depth_time=2026-10-29T18:30:15+00:00, book20_bid_proxy_usdt=179584, book20_ask_proxy_usdt=135770, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=6879882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=198.630000, depth_time=2026-10-29T18:30:19+00:00, book20_bid_proxy_usdt=95352, book20_ask_proxy_usdt=76127, funding_indicative=-0.000061, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=64655470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.039520, depth_time=2026-10-29T18:30:10+00:00, book20_bid_proxy_usdt=35415, book20_ask_proxy_usdt=65881, funding_indicative=0.000024, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=26753510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.053660, depth_time=2026-10-29T18:30:36+00:00, book20_bid_proxy_usdt=189125, book20_ask_proxy_usdt=246094, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=5749878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T18:30:00+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=1.725000, depth_time=2026-10-29T18:30:26+00:00, book20_bid_proxy_usdt=2223528, book20_ask_proxy_usdt=2244280, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.53%, turnover=6684487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T18:29:59+00:00, last15m_closed_end=2026-10-29T18:30+00:00, prior8high=0.441000, depth_time=2026-10-29T18:30:22+00:00, book20_bid_proxy_usdt=4564376, book20_ask_proxy_usdt=3928240, funding_indicative=0.000035, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=84643171. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
