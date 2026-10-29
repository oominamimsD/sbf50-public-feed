# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T11:15:36Z**
- feed_generated_utc: 2026-10-29T11:15:38+00:00
- source_sha256: `021f6150c55cec8ab5ff7c2bad455db725914ae3dc91e298041b207b03bef408`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T11:15+00:00, close=80187.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T11:00+00:00, close=80260.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T08:00+00:00, close=79827, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.044050|-29.25|-62.08|-28.83|32841484|2.27|
|EVAA_USDT|1.243600|-16.25|120.65|-15.83|21502767|5.61|
|BLESS_USDT|0.009756|-10.96|21.22|-10.54|19897226|5.14|
|JASMY_USDT|0.003823|-9.77|-21.59|-9.35|7063503|2.62|
|NEAR_USDT|4.424000|-4.42|-17.84|-4.00|108569811|2.26|
|DASH_USDT|50.750000|-4.31|-4.73|-3.89|13116345|1.97|
|BCH_USDT|281.010000|-4.07|-2.99|-3.65|5514804|4.27|
|HBAR_USDT|0.073820|-2.75|-14.10|-2.33|16278746|1.35|
|WLD_USDT|0.423700|-2.10|-26.13|-1.68|87196672|2.36|
|APT_USDT|0.674900|-2.00|-19.23|-1.58|8826440|1.48|
|SEI_USDT|0.051980|-1.64|-17.55|-1.22|5072960|1.93|
|XRP_USDT|1.291800|-1.47|-6.41|-1.05|296065759|0.77|
|DOT_USDT|0.989200|-1.43|-16.16|-1.01|11635833|1.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.674900|0.660600|0.675000|0.61|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|281.010000|279.210000|281.010000|1.04|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009756|0.009362|0.009756|3.08|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.750000|50.200000|50.750000|0.61|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.989200|0.976100|0.989200|1.48|N|N/Y|Y/Y|Y|N|
|EVAA_USDT|1.243600|1.060600|1.243600|1.68|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.073820|0.073590|0.073820|6.20|N|Y/Y|Y/Y|Y|N|
|JASMY_USDT|0.003823|0.003658|0.003826|1.20|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.424000|4.342000|4.424000|0.51|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.044050|0.041570|0.044050|0.63|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.051980|0.051210|0.051980|2.07|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.423700|0.416300|0.423700|1.29|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.291800|1.286700|1.291800|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.677200, depth_time=2026-10-29T11:15:28+00:00, book20_bid_proxy_usdt=143448, book20_ask_proxy_usdt=125707, funding_indicative=0.000056, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=8826440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=282.150000, depth_time=2026-10-29T11:15:18+00:00, book20_bid_proxy_usdt=88287, book20_ask_proxy_usdt=55857, funding_indicative=0.000074, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=5514804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.010299, depth_time=2026-10-29T11:15:12+00:00, book20_bid_proxy_usdt=9060, book20_ask_proxy_usdt=8908, funding_indicative=0.000050, next_funding_utc=2026-10-29T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.96%, turnover=19897226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=50.900000, depth_time=2026-10-29T11:15:16+00:00, book20_bid_proxy_usdt=690366, book20_ask_proxy_usdt=555400, funding_indicative=-0.000017, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.31%, turnover=13116345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.996000, depth_time=2026-10-29T11:15:34+00:00, book20_bid_proxy_usdt=413935, book20_ask_proxy_usdt=448842, funding_indicative=0.000059, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=11635833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T11:14:59+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=1.245000, depth_time=2026-10-29T11:15:10+00:00, book20_bid_proxy_usdt=9188, book20_ask_proxy_usdt=14544, funding_indicative=0.000110, next_funding_utc=2026-10-29T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.25%, turnover=21502767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.074100, depth_time=2026-10-29T11:15:23+00:00, book20_bid_proxy_usdt=920726, book20_ask_proxy_usdt=1118425, funding_indicative=0.000095, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=16278746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.003792, depth_time=2026-10-29T11:15:14+00:00, book20_bid_proxy_usdt=126046, book20_ask_proxy_usdt=113877, funding_indicative=-0.000545, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.77%, turnover=7063503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T11:14:59+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=4.438000, depth_time=2026-10-29T11:15:16+00:00, book20_bid_proxy_usdt=6024143, book20_ask_proxy_usdt=5712569, funding_indicative=0.000071, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.42%, turnover=108569811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T11:14:59+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.046740, depth_time=2026-10-29T11:15:07+00:00, book20_bid_proxy_usdt=35493, book20_ask_proxy_usdt=22849, funding_indicative=0.000170, next_funding_utc=2026-10-29T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.25%, turnover=32841484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.052170, depth_time=2026-10-29T11:15:30+00:00, book20_bid_proxy_usdt=191057, book20_ask_proxy_usdt=241178, funding_indicative=0.000084, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=5072960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T11:15:00+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=0.426400, depth_time=2026-10-29T11:15:25+00:00, book20_bid_proxy_usdt=4201238, book20_ask_proxy_usdt=4210524, funding_indicative=0.000065, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=87196672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T11:14:59+00:00, last15m_closed_end=2026-10-29T11:15+00:00, prior8high=1.296500, depth_time=2026-10-29T11:15:32+00:00, book20_bid_proxy_usdt=3432604, book20_ask_proxy_usdt=2954762, funding_indicative=0.000074, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=296065759. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
