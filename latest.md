# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T00:15:30Z**
- feed_generated_utc: 2026-10-23T00:15:32+00:00
- source_sha256: `9553aae4d8f08a55d9ea0523d1aa50a141578e51420eddfd94dade0de83caade`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T00:15+00:00, close=81209.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.372400|-6.69|9.08|-6.16|13384275|0.30|
|PUMPFUN_USDT|0.004550|-2.75|0.53|-2.22|36822604|2.20|
|XPL_USDT|0.075540|-2.52|-10.85|-1.99|5684161|1.32|
|XMR_USDT|598.240000|-2.39|9.97|-1.86|27090356|2.01|
|APT_USDT|0.754100|-2.34|-8.78|-1.81|8959187|3.98|
|STRK_USDT|0.053180|-2.17|-44.81|-1.64|12855021|1.88|
|ARB_USDT|0.180000|-1.98|-5.23|-1.45|32239731|0.56|
|QNT_USDT|187.000000|-1.94|-10.05|-1.41|58277778|0.53|
|SEI_USDT|0.057050|-1.75|-7.17|-1.22|9929503|1.75|
|TIA_USDT|0.558500|-1.74|-7.30|-1.21|23306503|1.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.754100|0.750100|0.754300|2.92|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.180000|0.177500|0.180020|0.71|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.372400|3.381700|3.372400|0.51|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.004550|0.004525|0.004551|1.45|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.000000|185.530000|187.050000|0.87|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057050|0.056780|0.057060|0.28|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053180|0.052550|0.053180|0.38|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.558500|0.555400|0.558500|2.97|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|598.240000|590.660000|598.340000|5.62|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.075540|0.075210|0.075540|3.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.761600, depth_time=2026-10-23T00:15:16+00:00, book20_bid_proxy_usdt=128267, book20_ask_proxy_usdt=160077, funding_indicative=-0.000056, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=8959187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.181730, depth_time=2026-10-23T00:15:21+00:00, book20_bid_proxy_usdt=124669, book20_ask_proxy_usdt=63176, funding_indicative=-0.000122, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=32239731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=3.508400, depth_time=2026-10-23T00:15:07+00:00, book20_bid_proxy_usdt=18928, book20_ask_proxy_usdt=29958, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.69%, turnover=13384275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.004649, depth_time=2026-10-23T00:15:09+00:00, book20_bid_proxy_usdt=1068429, book20_ask_proxy_usdt=1802692, funding_indicative=0.000021, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=36822604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=189.080000, depth_time=2026-10-23T00:15:24+00:00, book20_bid_proxy_usdt=49947, book20_ask_proxy_usdt=78402, funding_indicative=-0.000140, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=58277778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.057510, depth_time=2026-10-23T00:15:26+00:00, book20_bid_proxy_usdt=551584, book20_ask_proxy_usdt=473076, funding_indicative=-0.000017, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=9929503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.053350, depth_time=2026-10-23T00:15:19+00:00, book20_bid_proxy_usdt=588004, book20_ask_proxy_usdt=691106, funding_indicative=0.000040, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=12855021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.565100, depth_time=2026-10-23T00:15:29+00:00, book20_bid_proxy_usdt=317155, book20_ask_proxy_usdt=304737, funding_indicative=-0.000013, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=23306503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=602.780000, depth_time=2026-10-23T00:15:11+00:00, book20_bid_proxy_usdt=28792, book20_ask_proxy_usdt=13195, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=27090356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T00:14:59+00:00, last15m_closed_end=2026-10-23T00:15+00:00, prior8high=0.076290, depth_time=2026-10-23T00:15:11+00:00, book20_bid_proxy_usdt=364613, book20_ask_proxy_usdt=651310, funding_indicative=-0.000019, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=5684161. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
