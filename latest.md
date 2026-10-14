# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T08:00:29Z**
- feed_generated_utc: 2026-10-14T08:00:31+00:00
- source_sha256: `2486e6e07da9c0a41a4f66af4d433b824b07ddb5bd8cc52c3fc59f34b7c7a7cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056540|-19.91|29.38|-19.97|24546804|1.77|
|W_USDT|0.016410|-8.69|13.07|-8.75|6674205|3.05|
|MAGIC_USDT|0.112810|-4.84|65.60|-4.90|5222556|0.89|
|TIA_USDT|0.557500|-4.70|17.04|-4.76|39331021|3.59|
|STRK_USDT|0.082280|-3.67|57.65|-3.73|30167774|2.43|
|DOT_USDT|1.150500|-2.87|-4.23|-2.93|19034233|0.87|
|UNI_USDT|7.392000|-1.78|-14.69|-1.84|19044425|1.35|
|SILVER_USDT|58.770000|-1.40|-4.23|-1.46|247624703|1.70|
|ICP_USDT|3.100000|-1.30|-8.87|-1.36|9718404|3.23|
|XLM_USDT|0.189940|-1.07|-11.11|-1.13|9426233|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.150500|1.148800|1.150500|0.69|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.100000|3.076000|3.100000|0.52|N|Y/Y|Y/Y|N|N|
|MAGIC_USDT|0.112810|0.110660|0.112810|0.54|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.770000|58.510000|58.770000|0.38|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.082280|0.080270|0.082280|0.36|N|Y/Y|Y/Y|N|N|
|S_USDT|0.056540|0.055750|0.056540|1.32|N|Y/Y|N/N|N|N|
|TIA_USDT|0.557500|0.547400|0.557500|1.16|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.392000|7.259000|7.392000|0.42|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016410|0.015869|0.016410|0.53|N|Y/Y|Y/Y|N|N|
|XLM_USDT|0.189940|0.189130|0.189940|0.89|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=1.159800, depth_time=2026-10-14T08:00:18+00:00, book20_bid_proxy_usdt=223673, book20_ask_proxy_usdt=270382, funding_indicative=-0.000007, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=19034233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=3.113000, depth_time=2026-10-14T08:00:25+00:00, book20_bid_proxy_usdt=826362, book20_ask_proxy_usdt=825285, funding_indicative=0.000097, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=9718404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=0.114360, depth_time=2026-10-14T08:00:11+00:00, book20_bid_proxy_usdt=176981, book20_ask_proxy_usdt=166714, funding_indicative=-0.000011, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=5222556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=59.170000, depth_time=2026-10-14T08:00:22+00:00, book20_bid_proxy_usdt=46093953, book20_ask_proxy_usdt=34392619, funding_indicative=0.000074, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=247624703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=0.083840, depth_time=2026-10-14T08:00:15+00:00, book20_bid_proxy_usdt=261386, book20_ask_proxy_usdt=152419, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.67%, turnover=30167774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=0.057560, depth_time=2026-10-14T08:00:06+00:00, book20_bid_proxy_usdt=164701, book20_ask_proxy_usdt=81098, funding_indicative=-0.000075, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.91%, turnover=24546804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=0.571000, depth_time=2026-10-14T08:00:13+00:00, book20_bid_proxy_usdt=124410, book20_ask_proxy_usdt=149602, funding_indicative=0.000018, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=39331021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=7.396000, depth_time=2026-10-14T08:00:20+00:00, book20_bid_proxy_usdt=1223786, book20_ask_proxy_usdt=1539627, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=19044425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T08:00:01+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=0.016445, depth_time=2026-10-14T08:00:09+00:00, book20_bid_proxy_usdt=34483, book20_ask_proxy_usdt=38470, funding_indicative=-0.000240, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.69%, turnover=6674205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T08:00:02+00:00, last15m_closed_end=2026-10-14T08:00+00:00, prior8high=0.190630, depth_time=2026-10-14T08:00:27+00:00, book20_bid_proxy_usdt=190305, book20_ask_proxy_usdt=159836, funding_indicative=-0.000034, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=9426233. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
