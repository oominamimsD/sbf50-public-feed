# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T18:00:24Z**
- feed_generated_utc: 2026-10-29T18:00:26+00:00
- source_sha256: `f330187dddbb279144f4d18e4be75d8219ecb54797f1156b81f8a3f59ed3bc47`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T18:00+00:00, close=80857.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T18:00+00:00, close=80857.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.518000|-7.33|-15.19|-6.28|9631735|1.31|
|QNT_USDT|192.650000|-3.06|1.01|-2.01|63435153|1.04|
|TRUMPOFFICIAL_USDT|1.678000|-2.89|-3.78|-1.84|6640254|5.96|
|WLD_USDT|0.423800|-2.86|-20.35|-1.81|83711429|2.36|
|FARTCOIN_USDT|0.130600|-2.82|-8.56|-1.77|11163586|0.77|
|SEI_USDT|0.052070|-2.56|-10.33|-1.51|5670130|3.84|
|DOT_USDT|0.991900|-2.50|-11.77|-1.45|11063935|3.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.518000|1.509900|1.518000|1.17|N|Y/Y|Y/N|N|N|
|DOT_USDT|0.991900|0.993000|0.991400|1.29|N|Y/N|N/Y|N|N|
|FARTCOIN_USDT|0.130600|0.130460|0.130500|0.86|N|Y/N|N/Y|N|N|
|QNT_USDT|192.650000|191.690000|192.570000|1.01|N|Y/N|N/Y|N|N|
|SEI_USDT|0.052070|0.052110|0.052060|2.47|Y|Y/N|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.678000|1.678000|1.677000|3.70|Y|Y/N|N/Y|N|N|
|WLD_USDT|0.423800|0.422500|0.423600|1.26|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-29T18:00:03+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=1.645700, depth_time=2026-10-29T18:00:08+00:00, book20_bid_proxy_usdt=12751, book20_ask_proxy_usdt=25377, funding_indicative=-0.000049, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.33%, turnover=9631735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T18:00:04+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=1.023800, depth_time=2026-10-29T18:00:23+00:00, book20_bid_proxy_usdt=361864, book20_ask_proxy_usdt=1082875, funding_indicative=0.000081, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=11063935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-29T18:00:04+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=0.136060, depth_time=2026-10-29T18:00:18+00:00, book20_bid_proxy_usdt=80771, book20_ask_proxy_usdt=56820, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=11163586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T18:00:03+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=199.910000, depth_time=2026-10-29T18:00:10+00:00, book20_bid_proxy_usdt=103152, book20_ask_proxy_usdt=72694, funding_indicative=-0.000036, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=63435153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T18:00:04+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=0.053940, depth_time=2026-10-29T18:00:20+00:00, book20_bid_proxy_usdt=211596, book20_ask_proxy_usdt=188057, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=5670130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T18:00:04+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=1.739000, depth_time=2026-10-29T18:00:13+00:00, book20_bid_proxy_usdt=2283319, book20_ask_proxy_usdt=1721021, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=6640254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T18:00:03+00:00, last15m_closed_end=2026-10-29T18:00+00:00, prior8high=0.443700, depth_time=2026-10-29T18:00:16+00:00, book20_bid_proxy_usdt=2863816, book20_ask_proxy_usdt=4347408, funding_indicative=0.000040, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=83711429. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
