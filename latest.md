# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T08:45:26Z**
- feed_generated_utc: 2026-10-26T08:45:30+00:00
- source_sha256: `c3a97f58cff767b724b9e14bc11a34392c9b5524ff42447b15fdefaffac28621`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T08:45+00:00, close=80278, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.076120|-29.17|14.46|-28.76|6842998|1.31|
|IRYS_USDT|0.029310|-23.75|140.24|-23.34|13306662|3.42|
|BTW_USDT|1.489200|-10.22|-35.40|-9.81|11121345|2.01|
|APR_USDT|0.037760|-8.59|38.61|-8.18|9041301|2.65|
|WLD_USDT|0.442100|-3.17|-7.18|-2.76|70264145|2.26|
|XMR_USDT|590.910000|-2.69|1.44|-2.28|6270408|0.17|
|LIT_USDT|3.097800|-2.53|5.71|-2.12|5865396|0.32|
|DOT_USDT|1.018700|-1.97|-4.74|-1.56|10832561|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.037760|0.032200|0.037600|0.92|N|N/Y|N/N|Y|N|
|BTW_USDT|1.489200|1.440500|1.489400|2.54|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.076120|0.081270|0.076320|2.18|Y|Y/Y|N/N|Y|N|
|DOT_USDT|1.018700|1.002700|1.018700|1.64|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.029310|0.028940|0.029320|1.05|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.097800|3.052200|3.097800|0.33|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.442100|0.434300|0.442300|2.18|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.910000|583.530000|590.910000|1.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T08:45:02+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=0.039060, depth_time=2026-10-26T08:45:15+00:00, book20_bid_proxy_usdt=55505, book20_ask_proxy_usdt=63111, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.59%, turnover=9041301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T08:45:03+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=1.621200, depth_time=2026-10-26T08:45:13+00:00, book20_bid_proxy_usdt=15664, book20_ask_proxy_usdt=28836, funding_indicative=-0.006955, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=11121345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T08:45:02+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=0.111390, depth_time=2026-10-26T08:45:08+00:00, book20_bid_proxy_usdt=64813, book20_ask_proxy_usdt=57032, funding_indicative=0.000233, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.17%, turnover=6842998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T08:45:03+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=1.014000, depth_time=2026-10-26T08:45:25+00:00, book20_bid_proxy_usdt=400666, book20_ask_proxy_usdt=254604, funding_indicative=-0.000055, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=10832561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T08:45:03+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=0.031910, depth_time=2026-10-26T08:45:09+00:00, book20_bid_proxy_usdt=63834, book20_ask_proxy_usdt=85603, funding_indicative=-0.000096, next_funding_utc=2026-10-26T09:00:00+00:00, funding_cycle_h=1, 24h_change=-23.75%, turnover=13306662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T08:45:03+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=3.131600, depth_time=2026-10-26T08:45:22+00:00, book20_bid_proxy_usdt=19393, book20_ask_proxy_usdt=19150, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=5865396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T08:45:03+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=0.441300, depth_time=2026-10-26T08:45:17+00:00, book20_bid_proxy_usdt=2913639, book20_ask_proxy_usdt=2535368, funding_indicative=-0.000075, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=70264145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T08:45:03+00:00, last15m_closed_end=2026-10-26T08:45+00:00, prior8high=589.000000, depth_time=2026-10-26T08:45:20+00:00, book20_bid_proxy_usdt=15353, book20_ask_proxy_usdt=17401, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=6270408. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
