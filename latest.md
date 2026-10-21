# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T22:30:38Z**
- feed_generated_utc: 2026-10-21T22:30:42+00:00
- source_sha256: `8e3ed5a5c1614e50c6118d06a27421224cafba6bd33ae58878797c958fdd8700`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T22:30+00:00, close=84566.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T22:00+00:00, close=84800, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.490000|-9.52|20.17|-9.60|14963556|0.61|
|AKE_USDT|0.024583|-7.89|-5.01|-7.97|10575627|2.44|
|ZRO_USDT|1.949600|-7.03|2.94|-7.11|7606469|0.51|
|STRK_USDT|0.059230|-4.42|-23.25|-4.50|23467560|1.69|
|TIA_USDT|0.610000|-3.55|14.33|-3.63|39789132|1.64|
|DOT_USDT|1.152100|-2.35|2.45|-2.43|16578706|0.87|
|FET_USDT|0.196000|-2.29|-3.87|-2.37|7606474|5.10|
|LDO_USDT|0.407300|-1.90|0.36|-1.98|5181284|2.46|
|ICP_USDT|2.916000|-1.68|-2.70|-1.76|5263459|3.43|
|AVAX_USDT|9.750000|-1.67|-0.68|-1.75|155632994|1.02|
|AAVE_USDT|155.920000|-1.63|0.01|-1.71|132920961|2.56|
|APT_USDT|0.822000|-1.62|3.95|-1.70|8139888|1.22|
|OP_USDT|0.129810|-1.58|-6.16|-1.66|6529563|0.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.920000|156.010000|155.930000|1.00|N|N/N|N/N|N|N|
|AKE_USDT|0.024583|0.024671|0.024583|1.15|N|Y/Y|Y/Y|N|N|
|APT_USDT|0.822000|0.821200|0.821600|0.48|N|N/N|N/N|N|N|
|AVAX_USDT|9.750000|9.754000|9.747000|1.48|Y|N/N|N/N|N|N|
|BR_USDT|0.490000|0.476600|0.490000|0.63|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.152100|1.157300|1.152100|1.54|Y|Y/N|N/N|N|N|
|FET_USDT|0.196000|0.196500|0.195900|1.51|Y|N/N|N/N|N|N|
|ICP_USDT|2.916000|2.912000|2.916000|3.22|N|N/N|N/N|N|N|
|LDO_USDT|0.407300|0.407300|0.407300|1.51|N|Y/Y|N/N|N|N|
|OP_USDT|0.129810|0.129950|0.129810|0.98|N|N/N|N/N|N|N|
|STRK_USDT|0.059230|0.059030|0.059230|1.84|N|N/N|N/N|N|N|
|TIA_USDT|0.610000|0.611700|0.609800|1.32|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.949600|1.958900|1.949600|5.69|Y|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=158.100000, depth_time=2026-10-21T22:30:31+00:00, book20_bid_proxy_usdt=300289, book20_ask_proxy_usdt=367604, funding_indicative=-0.000025, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=132920961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.026307, depth_time=2026-10-21T22:30:11+00:00, book20_bid_proxy_usdt=15237, book20_ask_proxy_usdt=14659, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.89%, turnover=10575627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.833600, depth_time=2026-10-21T22:30:35+00:00, book20_bid_proxy_usdt=113566, book20_ask_proxy_usdt=183402, funding_indicative=0.000061, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=8139888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=9.883000, depth_time=2026-10-21T22:30:30+00:00, book20_bid_proxy_usdt=932443, book20_ask_proxy_usdt=1148227, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=155632994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.504950, depth_time=2026-10-21T22:30:08+00:00, book20_bid_proxy_usdt=3757, book20_ask_proxy_usdt=13693, funding_indicative=-0.000145, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.52%, turnover=14963556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=1.176100, depth_time=2026-10-21T22:30:21+00:00, book20_bid_proxy_usdt=290101, book20_ask_proxy_usdt=277118, funding_indicative=-0.000111, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=16578706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.200300, depth_time=2026-10-21T22:30:22+00:00, book20_bid_proxy_usdt=1556174, book20_ask_proxy_usdt=1229633, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=7606474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=2.959000, depth_time=2026-10-21T22:30:28+00:00, book20_bid_proxy_usdt=785866, book20_ask_proxy_usdt=713469, funding_indicative=-0.000021, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=5263459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.412800, depth_time=2026-10-21T22:30:25+00:00, book20_bid_proxy_usdt=668316, book20_ask_proxy_usdt=583947, funding_indicative=0.000003, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=5181284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.132920, depth_time=2026-10-21T22:30:37+00:00, book20_bid_proxy_usdt=138049, book20_ask_proxy_usdt=92291, funding_indicative=0.000018, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=6529563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.061590, depth_time=2026-10-21T22:30:16+00:00, book20_bid_proxy_usdt=368708, book20_ask_proxy_usdt=557946, funding_indicative=0.000018, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=23467560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=0.625800, depth_time=2026-10-21T22:30:19+00:00, book20_bid_proxy_usdt=232088, book20_ask_proxy_usdt=310209, funding_indicative=-0.000123, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=39789132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T22:30:03+00:00, last15m_closed_end=2026-10-21T22:30+00:00, prior8high=2.022100, depth_time=2026-10-21T22:30:13+00:00, book20_bid_proxy_usdt=34525, book20_ask_proxy_usdt=82406, funding_indicative=-0.000020, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.03%, turnover=7606469. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
