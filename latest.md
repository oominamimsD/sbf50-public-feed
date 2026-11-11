# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T05:00:27Z**
- feed_generated_utc: 2026-11-11T05:00:28+00:00
- source_sha256: `fb2d45ea4d4476a39b155da28ee9597128251c90aba9ab10913c864386c0b250`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T05:00+00:00, close=73703.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T05:00+00:00, close=73703.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1015.910000|-7.08|-15.60|-7.79|2127179788|0.10|
|UNI_USDT|6.666000|-5.64|-9.34|-6.35|35921240|1.50|
|DASH_USDT|44.150000|-2.19|-4.31|-2.90|14481791|2.27|
|DOT_USDT|0.844400|-2.09|-10.41|-2.80|7860239|1.18|
|HYPE_USDT|72.102000|-2.05|-17.45|-2.76|38129130|0.14|
|XRP_USDT|1.054100|-1.04|-17.69|-1.75|325522800|0.95|
|VVV_USDT|19.106000|-0.69|-14.55|-1.40|5292201|0.52|
|QNT_USDT|179.960000|-0.40|-7.91|-1.11|45070067|2.22|
|HBAR_USDT|0.065560|-0.33|-6.38|-1.04|7364080|1.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|44.150000|43.290000|44.140000|0.28|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.844400|0.841400|0.844400|1.21|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065560|0.065540|0.065570|4.15|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|72.102000|71.654000|72.102000|0.29|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|179.960000|179.480000|180.010000|0.94|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.666000|6.651000|6.666000|1.08|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.106000|19.117000|19.111000|1.13|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.054100|1.049300|1.054100|0.35|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1015.910000|1012.300000|1015.730000|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=44.810000, depth_time=2026-11-11T05:00:12+00:00, book20_bid_proxy_usdt=330435, book20_ask_proxy_usdt=584979, funding_indicative=-0.000153, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=14481791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=0.849300, depth_time=2026-11-11T05:00:12+00:00, book20_bid_proxy_usdt=851867, book20_ask_proxy_usdt=497383, funding_indicative=0.000060, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=7860239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=0.066370, depth_time=2026-11-11T05:00:22+00:00, book20_bid_proxy_usdt=741423, book20_ask_proxy_usdt=703254, funding_indicative=-0.000004, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.33%, turnover=7364080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=72.421000, depth_time=2026-11-11T05:00:17+00:00, book20_bid_proxy_usdt=159082, book20_ask_proxy_usdt=134154, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=38129130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=181.920000, depth_time=2026-11-11T05:00:24+00:00, book20_bid_proxy_usdt=59458, book20_ask_proxy_usdt=104218, funding_indicative=-0.000125, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.40%, turnover=45070067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=6.768000, depth_time=2026-11-11T05:00:09+00:00, book20_bid_proxy_usdt=2960922, book20_ask_proxy_usdt=3149259, funding_indicative=0.000053, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.64%, turnover=35921240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=19.529000, depth_time=2026-11-11T05:00:18+00:00, book20_bid_proxy_usdt=50347, book20_ask_proxy_usdt=22419, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.69%, turnover=5292201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=1.065200, depth_time=2026-11-11T05:00:19+00:00, book20_bid_proxy_usdt=3506955, book20_ask_proxy_usdt=4343253, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=325522800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T05:00:02+00:00, last15m_closed_end=2026-11-11T05:00+00:00, prior8high=1038.490000, depth_time=2026-11-11T05:00:06+00:00, book20_bid_proxy_usdt=357320, book20_ask_proxy_usdt=618699, funding_indicative=0.000098, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.08%, turnover=2127179788. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
