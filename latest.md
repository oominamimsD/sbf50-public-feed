# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T10:15:32Z**
- feed_generated_utc: 2026-10-20T10:15:35+00:00
- source_sha256: `b4853e7d39adf28733a44acf27cd2723fe03b460783c6a95816da44b7076cd80`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T10:15+00:00, close=81571.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T10:00+00:00, close=81450, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.070217|-19.32|321.41|-18.90|9535293|1.42|
|Q_USDT|0.118493|-5.94|284.82|-5.52|6418569|2.78|
|NEAR_USDT|4.691000|-4.34|-15.46|-3.92|170040236|2.13|
|SAND_USDT|0.056620|-4.26|-8.80|-3.84|5536948|1.77|
|ARB_USDT|0.189210|-3.28|0.39|-2.86|95613750|0.53|
|ATOM_USDT|1.718000|-3.26|-6.01|-2.84|5196760|5.82|
|BTW_USDT|1.706500|-2.59|-2.80|-2.17|34128794|1.17|
|UNI_USDT|7.128000|-2.19|-3.90|-1.77|10253348|1.40|
|TAO_USDT|263.100000|-1.93|-8.10|-1.51|58984252|1.14|
|SEI_USDT|0.059700|-1.59|-10.04|-1.17|6080687|1.68|
|AVAX_USDT|9.419000|-1.49|-11.81|-1.07|141957627|1.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.070217|0.066550|0.070217|2.03|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189210|0.188850|0.189210|0.80|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.718000|1.711000|1.718000|0.18|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.419000|9.402000|9.419000|0.74|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.706500|1.486000|1.706600|1.52|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.691000|4.693000|4.691000|1.17|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.118493|0.117109|0.118565|1.97|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056620|0.056320|0.056620|1.91|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059700|0.059410|0.059700|1.00|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.100000|261.790000|263.100000|0.93|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.128000|7.093000|7.128000|0.32|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=0.077888, depth_time=2026-10-20T10:15:07+00:00, book20_bid_proxy_usdt=5036, book20_ask_proxy_usdt=4180, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.32%, turnover=9535293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=0.193230, depth_time=2026-10-20T10:15:16+00:00, book20_bid_proxy_usdt=68676, book20_ask_proxy_usdt=61895, funding_indicative=0.000093, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=95613750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=1.741000, depth_time=2026-10-20T10:15:18+00:00, book20_bid_proxy_usdt=1499743, book20_ask_proxy_usdt=1143607, funding_indicative=0.000082, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=5196760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=9.507000, depth_time=2026-10-20T10:15:31+00:00, book20_bid_proxy_usdt=1061325, book20_ask_proxy_usdt=1007764, funding_indicative=0.000006, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=141957627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=1.672200, depth_time=2026-10-20T10:15:22+00:00, book20_bid_proxy_usdt=9368, book20_ask_proxy_usdt=11260, funding_indicative=-0.004006, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=34128794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=4.782000, depth_time=2026-10-20T10:15:11+00:00, book20_bid_proxy_usdt=3627324, book20_ask_proxy_usdt=3910543, funding_indicative=0.000061, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=170040236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=0.129136, depth_time=2026-10-20T10:15:10+00:00, book20_bid_proxy_usdt=13292, book20_ask_proxy_usdt=14574, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.94%, turnover=6418569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=0.056910, depth_time=2026-10-20T10:15:13+00:00, book20_bid_proxy_usdt=1053519, book20_ask_proxy_usdt=870987, funding_indicative=-0.001593, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=5536948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=0.060160, depth_time=2026-10-20T10:15:29+00:00, book20_bid_proxy_usdt=243597, book20_ask_proxy_usdt=243234, funding_indicative=0.000004, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=6080687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=264.420000, depth_time=2026-10-20T10:15:27+00:00, book20_bid_proxy_usdt=160461, book20_ask_proxy_usdt=108620, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=58984252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T10:14:59+00:00, last15m_closed_end=2026-10-20T10:15+00:00, prior8high=7.186000, depth_time=2026-10-20T10:15:23+00:00, book20_bid_proxy_usdt=1873901, book20_ask_proxy_usdt=2002570, funding_indicative=0.000083, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=10253348. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
