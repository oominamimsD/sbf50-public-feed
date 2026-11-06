# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T23:00:24Z**
- feed_generated_utc: 2026-11-06T23:00:25+00:00
- source_sha256: `64492d6f4ac71fdb319255a27a4cb95cacff246a1c13e18e7f63b16c150242ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T23:00+00:00, close=75873.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T23:00+00:00, close=75873.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.137100|-27.84|-48.38|-27.91|33767037|7.29|
|JCT_USDT|0.003201|-9.49|-44.18|-9.56|5201632|3.12|
|ANTHROPIC_USDT|1340.280000|-7.79|-20.05|-7.86|7181921|1.72|
|PUMPFUN_USDT|0.003940|-3.90|-4.06|-3.97|12526663|2.54|
|LIT_USDT|3.317800|-2.05|17.47|-2.12|9599234|0.30|
|NEAR_USDT|3.702000|-1.67|-14.34|-1.74|44792085|2.70|
|HBAR_USDT|0.067480|-1.34|-6.08|-1.41|5611250|2.96|
|XRP_USDT|1.176000|-0.96|-6.25|-1.03|349334232|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1340.280000|1309.270000|1340.280000|0.59|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067480|0.067590|0.067470|1.14|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.003201|0.003184|0.003201|0.88|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.317800|3.283100|3.317800|0.34|N|Y/Y|Y/N|Y|N|
|NEAR_USDT|3.702000|3.699000|3.702000|0.93|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003940|0.003935|0.003940|0.23|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.137100|0.128700|0.136500|0.51|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.176000|1.171500|1.175700|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=1364.960000, depth_time=2026-11-06T23:00:11+00:00, book20_bid_proxy_usdt=19234, book20_ask_proxy_usdt=31947, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.79%, turnover=7181921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=0.068220, depth_time=2026-11-06T23:00:19+00:00, book20_bid_proxy_usdt=707177, book20_ask_proxy_usdt=814435, funding_indicative=0.000041, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=5611250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=0.003279, depth_time=2026-11-06T23:00:09+00:00, book20_bid_proxy_usdt=110559, book20_ask_proxy_usdt=86842, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.49%, turnover=5201632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=3.375500, depth_time=2026-11-06T23:00:15+00:00, book20_bid_proxy_usdt=143275, book20_ask_proxy_usdt=34313, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=9599234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=3.755000, depth_time=2026-11-06T23:00:18+00:00, book20_bid_proxy_usdt=2498600, book20_ask_proxy_usdt=2217489, funding_indicative=0.000100, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=44792085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=0.004011, depth_time=2026-11-06T23:00:14+00:00, book20_bid_proxy_usdt=2567526, book20_ask_proxy_usdt=2256969, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=12526663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=0.149300, depth_time=2026-11-06T23:00:07+00:00, book20_bid_proxy_usdt=175356, book20_ask_proxy_usdt=129454, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-27.84%, turnover=33767037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T23:00:02+00:00, last15m_closed_end=2026-11-06T23:00+00:00, prior8high=1.184700, depth_time=2026-11-06T23:00:22+00:00, book20_bid_proxy_usdt=4113451, book20_ask_proxy_usdt=1876132, funding_indicative=0.000059, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=349334232. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
