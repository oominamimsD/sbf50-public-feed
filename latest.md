# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T17:30:19Z**
- feed_generated_utc: 2026-10-24T17:30:23+00:00
- source_sha256: `47d642b39f97bd30ece9e200520205fb3922fd81ff44a2f596de0a31c117c927`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T17:30+00:00, close=80160.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T17:00+00:00, close=80182.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.095960|-1.74|97.77|-2.24|12025189|1.04|
|DOT_USDT|1.029300|-0.94|-7.88|-1.44|13332472|0.97|
|TIA_USDT|0.521000|-0.89|-20.82|-1.39|30668922|1.92|
|ARB_USDT|0.164500|-0.74|-10.55|-1.24|24227940|0.61|
|AGT_USDT|0.066520|-0.61|-7.68|-1.11|10409948|7.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066520|0.064320|0.066550|0.84|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.164500|0.163630|0.164600|0.42|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.095960|0.091630|0.095960|0.38|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.029300|1.022400|1.029300|0.82|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.521000|0.516000|0.520800|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T17:30:00+00:00, last15m_closed_end=2026-10-24T17:30+00:00, prior8high=0.071110, depth_time=2026-10-24T17:30:18+00:00, book20_bid_proxy_usdt=10612, book20_ask_proxy_usdt=9683, funding_indicative=0.000129, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.61%, turnover=10409948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-24T17:30:00+00:00, last15m_closed_end=2026-10-24T17:30+00:00, prior8high=0.166400, depth_time=2026-10-24T17:30:15+00:00, book20_bid_proxy_usdt=151260, book20_ask_proxy_usdt=50452, funding_indicative=0.000033, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=24227940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T17:30:00+00:00, last15m_closed_end=2026-10-24T17:30+00:00, prior8high=0.102970, depth_time=2026-10-24T17:30:08+00:00, book20_bid_proxy_usdt=11337, book20_ask_proxy_usdt=10767, funding_indicative=-0.007967, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=12025189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T17:30:00+00:00, last15m_closed_end=2026-10-24T17:30+00:00, prior8high=1.042100, depth_time=2026-10-24T17:30:11+00:00, book20_bid_proxy_usdt=234775, book20_ask_proxy_usdt=224476, funding_indicative=-0.000082, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=13332472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T17:30:00+00:00, last15m_closed_end=2026-10-24T17:30+00:00, prior8high=0.531400, depth_time=2026-10-24T17:30:12+00:00, book20_bid_proxy_usdt=197845, book20_ask_proxy_usdt=263673, funding_indicative=0.000000, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=30668922. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
