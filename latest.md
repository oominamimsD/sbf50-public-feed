# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T10:30:35Z**
- feed_generated_utc: 2026-10-31T10:30:37+00:00
- source_sha256: `ba6113cf848d5be9e8534af59ef928ad3ac7b205b6c899f484c055f828b154b4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T10:30+00:00, close=77485, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T10:00+00:00, close=77434.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010500|-44.50|-69.99|-44.38|10185311|3.81|
|Q_USDT|0.031990|-32.62|-72.96|-32.50|14320936|9.39|
|IDOL_USDT|0.018591|-8.15|134.73|-8.03|15985501|7.03|
|BTW_USDT|1.128500|-5.91|-33.71|-5.79|9051944|3.54|
|TRX_USDT|0.316890|-5.54|-3.78|-5.42|7260620|0.32|
|HYPE_USDT|88.047000|-4.65|12.29|-4.53|105416644|0.11|
|WLD_USDT|0.396700|-3.69|-25.48|-3.57|48238159|2.52|
|FET_USDT|0.162000|-2.76|-13.50|-2.64|5921571|6.18|
|DASH_USDT|48.060000|-1.99|-10.75|-1.87|13060530|2.08|
|LTC_USDT|54.980000|-1.32|-5.93|-1.20|6363195|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010500|0.010379|0.010500|0.47|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.128500|1.124400|1.129000|0.73|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.060000|47.590000|48.060000|0.28|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.162000|0.161100|0.162000|0.68|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.047000|86.343000|88.048000|2.67|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.018591|0.018443|0.018591|2.45|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.980000|54.520000|54.990000|0.72|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031990|0.031080|0.031990|0.61|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.316890|0.316350|0.316890|1.63|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396700|0.394600|0.396700|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=0.011333, depth_time=2026-10-31T10:30:09+00:00, book20_bid_proxy_usdt=17174, book20_ask_proxy_usdt=7866, funding_indicative=-0.000470, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-44.50%, turnover=10185311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=1.167600, depth_time=2026-10-31T10:30:18+00:00, book20_bid_proxy_usdt=27646, book20_ask_proxy_usdt=25219, funding_indicative=-0.000175, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.91%, turnover=9051944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T10:30:02+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=47.930000, depth_time=2026-10-31T10:30:30+00:00, book20_bid_proxy_usdt=706438, book20_ask_proxy_usdt=546716, funding_indicative=-0.000109, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=13060530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T10:30:02+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=0.162400, depth_time=2026-10-31T10:30:21+00:00, book20_bid_proxy_usdt=1195167, book20_ask_proxy_usdt=901704, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=5921571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=87.926000, depth_time=2026-10-31T10:30:23+00:00, book20_bid_proxy_usdt=175024, book20_ask_proxy_usdt=101042, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=105416644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=0.022481, depth_time=2026-10-31T10:30:15+00:00, book20_bid_proxy_usdt=5866, book20_ask_proxy_usdt=13429, funding_indicative=0.000272, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.15%, turnover=15985501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T10:30:02+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=54.990000, depth_time=2026-10-31T10:30:33+00:00, book20_bid_proxy_usdt=1398179, book20_ask_proxy_usdt=1182615, funding_indicative=-0.000028, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=6363195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=0.033810, depth_time=2026-10-31T10:30:13+00:00, book20_bid_proxy_usdt=41284, book20_ask_proxy_usdt=57319, funding_indicative=-0.000578, next_funding_utc=2026-10-31T11:00:00+00:00, funding_cycle_h=1, 24h_change=-32.62%, turnover=14320936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=0.321660, depth_time=2026-10-31T10:30:20+00:00, book20_bid_proxy_usdt=57741, book20_ask_proxy_usdt=43993, funding_indicative=-0.000915, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=7260620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T10:30:01+00:00, last15m_closed_end=2026-10-31T10:30+00:00, prior8high=0.399000, depth_time=2026-10-31T10:30:26+00:00, book20_bid_proxy_usdt=3168786, book20_ask_proxy_usdt=2675027, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=48238159. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
