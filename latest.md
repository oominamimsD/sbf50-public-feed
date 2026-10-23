# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T07:30:24Z**
- feed_generated_utc: 2026-10-23T07:30:25+00:00
- source_sha256: `06e8ff60b2decee5c6a4534bbce2fe538f1fb834d54e282ac77ce1d6431ec8d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T07:30+00:00, close=81692.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T07:00+00:00, close=81851.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004271|-7.31|115.16|-7.36|8271793|9.37|
|LIT_USDT|3.430300|-5.08|10.96|-5.13|9906104|0.29|
|SILVER_USDT|53.950000|-2.37|-5.58|-2.42|341448629|1.85|
|STRK_USDT|0.053150|-2.22|-44.84|-2.27|10479882|1.88|
|TIA_USDT|0.558800|-1.68|-7.25|-1.73|23998113|1.79|
|PUMPFUN_USDT|0.004619|-1.28|2.05|-1.33|37642451|2.17|
|QNT_USDT|188.570000|-1.12|-9.30|-1.17|49114679|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004271|0.004159|0.004271|0.72|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.430300|3.409600|3.430300|0.39|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004619|0.004619|0.004619|1.41|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.570000|187.970000|188.570000|1.11|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.950000|54.020000|53.950000|1.10|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053150|0.052400|0.053150|0.08|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.558800|0.556900|0.558800|1.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=0.004429, depth_time=2026-10-23T07:30:06+00:00, book20_bid_proxy_usdt=37667, book20_ask_proxy_usdt=28572, funding_indicative=0.000067, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.31%, turnover=8271793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=3.469700, depth_time=2026-10-23T07:30:10+00:00, book20_bid_proxy_usdt=49300, book20_ask_proxy_usdt=29767, funding_indicative=0.000004, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.08%, turnover=9906104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=0.004684, depth_time=2026-10-23T07:30:19+00:00, book20_bid_proxy_usdt=1860897, book20_ask_proxy_usdt=1852546, funding_indicative=0.000006, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=37642451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=190.340000, depth_time=2026-10-23T07:30:23+00:00, book20_bid_proxy_usdt=80834, book20_ask_proxy_usdt=108740, funding_indicative=-0.000133, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=49114679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=54.680000, depth_time=2026-10-23T07:30:12+00:00, book20_bid_proxy_usdt=33113243, book20_ask_proxy_usdt=30110061, funding_indicative=0.000154, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=341448629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=0.053510, depth_time=2026-10-23T07:30:15+00:00, book20_bid_proxy_usdt=571804, book20_ask_proxy_usdt=588990, funding_indicative=-0.000030, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=10479882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T07:30:00+00:00, last15m_closed_end=2026-10-23T07:30+00:00, prior8high=0.562000, depth_time=2026-10-23T07:30:17+00:00, book20_bid_proxy_usdt=436721, book20_ask_proxy_usdt=327802, funding_indicative=-0.000034, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=23998113. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
