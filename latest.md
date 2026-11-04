# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T20:30:28Z**
- feed_generated_utc: 2026-11-04T20:30:30+00:00
- source_sha256: `58eed02380b23cc341ce56735afb51aaa8eb30bca2bc45da03e48077bdc66e4e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T20:30+00:00, close=80173.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.275000|-10.46|-25.39|-10.35|25175857|7.84|
|AGT_USDT|0.032380|-9.80|-28.18|-9.69|5098338|6.18|
|AKE_USDT|0.002580|-8.18|-87.16|-8.07|17100346|3.89|
|BTW_USDT|1.036800|-5.65|-40.34|-5.54|6566495|0.96|
|PUMPFUN_USDT|0.004226|-5.03|0.45|-4.92|19287826|2.37|
|OP_USDT|0.109810|-3.84|-1.14|-3.73|11755288|0.91|
|ZRO_USDT|1.793200|-3.83|4.74|-3.72|11441035|0.56|
|WLD_USDT|0.377700|-3.67|-12.73|-3.56|76695266|2.65|
|HYPE_USDT|83.881000|-2.35|5.03|-2.24|90017700|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032380|0.031770|0.032390|0.25|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002580|0.002455|0.002580|0.45|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.036800|1.046200|1.036800|0.71|N|N/N|Y/N|N|N|
|HYPE_USDT|83.881000|83.096000|83.926000|0.75|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.109810|0.108620|0.109820|0.79|N|Y/Y|Y/N|N|N|
|PUMPFUN_USDT|0.004226|0.004138|0.004226|0.40|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.275000|1.280000|1.275000|0.78|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377700|0.370800|0.377700|1.17|N|Y/Y|Y/N|N|N|
|ZRO_USDT|1.793200|1.757900|1.793200|1.48|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T20:30:02+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=0.033440, depth_time=2026-11-04T20:30:10+00:00, book20_bid_proxy_usdt=41192, book20_ask_proxy_usdt=27257, funding_indicative=0.000053, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.80%, turnover=5098338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T20:30:02+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=0.002774, depth_time=2026-11-04T20:30:13+00:00, book20_bid_proxy_usdt=103111, book20_ask_proxy_usdt=63241, funding_indicative=-0.000532, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.18%, turnover=17100346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T20:30:03+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=1.079200, depth_time=2026-11-04T20:30:15+00:00, book20_bid_proxy_usdt=18653, book20_ask_proxy_usdt=19105, funding_indicative=0.000007, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.65%, turnover=6566495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T20:30:02+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=85.099000, depth_time=2026-11-04T20:30:27+00:00, book20_bid_proxy_usdt=53707, book20_ask_proxy_usdt=189801, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=90017700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T20:30:03+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=0.112320, depth_time=2026-11-04T20:30:20+00:00, book20_bid_proxy_usdt=106414, book20_ask_proxy_usdt=101787, funding_indicative=0.000055, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=11755288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T20:30:03+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=0.004277, depth_time=2026-11-04T20:30:17+00:00, book20_bid_proxy_usdt=1947355, book20_ask_proxy_usdt=2056452, funding_indicative=0.000048, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=19287826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T20:30:02+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=1.327000, depth_time=2026-11-04T20:30:08+00:00, book20_bid_proxy_usdt=1239656, book20_ask_proxy_usdt=894527, funding_indicative=-0.000292, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=25175857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T20:30:02+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=0.383900, depth_time=2026-11-04T20:30:25+00:00, book20_bid_proxy_usdt=2293852, book20_ask_proxy_usdt=2075453, funding_indicative=-0.000469, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=76695266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T20:30:03+00:00, last15m_closed_end=2026-11-04T20:30+00:00, prior8high=1.842000, depth_time=2026-11-04T20:30:21+00:00, book20_bid_proxy_usdt=31354, book20_ask_proxy_usdt=46188, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=11441035. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
