# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T01:15:42Z**
- feed_generated_utc: 2026-10-22T01:15:44+00:00
- source_sha256: `f5129f6b56cc6c7894a2231b1e34bcf39ba3994e99f999bf9d27cd425113ac9e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T01:15+00:00, close=84231, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T01:00+00:00, close=84159, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000935|-36.12|16.85|-35.81|15236103|4.27|
|DOOD_USDT|0.002201|-22.60|55.21|-22.29|9036239|4.55|
|BR_USDT|0.477530|-11.82|17.11|-11.51|14401775|0.21|
|AKE_USDT|0.023690|-11.24|-8.46|-10.93|10991725|2.96|
|STRK_USDT|0.057740|-6.82|-25.18|-6.51|24063178|3.46|
|ZRO_USDT|1.976300|-5.76|4.35|-5.45|7337694|0.51|
|TIA_USDT|0.606300|-4.14|13.64|-3.83|37879435|1.65|
|AVAX_USDT|9.708000|-2.09|-1.11|-1.78|158058353|1.03|
|DOT_USDT|1.159100|-1.76|3.07|-1.45|17036564|2.59|
|ICP_USDT|2.916000|-1.68|-2.70|-1.37|5748256|3.43|
|DOGE_USDT|0.082060|-1.66|0.09|-1.35|82293062|1.22|
|INJ_USDT|8.614000|-1.64|12.76|-1.33|48599817|1.16|
|AAVE_USDT|155.920000|-1.63|0.01|-1.32|131713932|0.64|
|OP_USDT|0.129760|-1.62|-6.20|-1.31|6716142|2.31|
|LDO_USDT|0.408900|-1.51|0.76|-1.20|5167906|2.45|
|TAO_USDT|273.350000|-1.50|2.01|-1.19|60541824|1.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.920000|154.590000|155.960000|1.51|N|Y/Y|N/N|N|N|
|AKE_USDT|0.023690|0.023415|0.023690|0.95|N|Y/Y|Y/Y|N|N|
|AVAX_USDT|9.708000|9.639000|9.707000|1.75|N|Y/Y|Y/N|N|N|
|BR_USDT|0.477530|0.472700|0.477530|0.84|N|Y/Y|Y/Y|N|N|
|DOGE_USDT|0.082060|0.081730|0.082060|1.00|N|Y/Y|N/N|N|N|
|DOOD_USDT|0.002201|0.002241|0.002199|1.43|Y|Y/Y|N/N|N|N|
|DOT_USDT|1.159100|1.139000|1.159100|0.67|N|Y/Y|Y/N|N|N|
|ICP_USDT|2.916000|2.880000|2.916000|0.54|N|Y/Y|Y/N|N|N|
|INJ_USDT|8.614000|8.544000|8.614000|0.42|N|Y/Y|Y/Y|N|N|
|IOST_USDT|0.000935|0.000930|0.000935|1.66|N|Y/Y|Y/N|N|N|
|LDO_USDT|0.408900|0.402400|0.408900|0.55|N|Y/Y|N/N|N|N|
|OP_USDT|0.129760|0.128270|0.129840|0.44|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.057740|0.056630|0.057790|0.24|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.606300|0.595900|0.606300|1.20|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.976300|1.935400|1.976300|0.72|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=156.090000, depth_time=2026-10-22T01:15:36+00:00, book20_bid_proxy_usdt=297666, book20_ask_proxy_usdt=318896, funding_indicative=-0.000013, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=131713932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.024720, depth_time=2026-10-22T01:15:15+00:00, book20_bid_proxy_usdt=14779, book20_ask_proxy_usdt=17023, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.24%, turnover=10991725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=9.717000, depth_time=2026-10-22T01:15:24+00:00, book20_bid_proxy_usdt=986676, book20_ask_proxy_usdt=967421, funding_indicative=-0.000011, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=158058353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.492440, depth_time=2026-10-22T01:15:12+00:00, book20_bid_proxy_usdt=6940, book20_ask_proxy_usdt=2626, funding_indicative=-0.000225, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.82%, turnover=14401775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.082280, depth_time=2026-10-22T01:15:31+00:00, book20_bid_proxy_usdt=3879992, book20_ask_proxy_usdt=4149483, funding_indicative=0.000019, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=82293062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.002454, depth_time=2026-10-22T01:15:10+00:00, book20_bid_proxy_usdt=106512, book20_ask_proxy_usdt=154150, funding_indicative=-0.000444, next_funding_utc=2026-10-22T02:00:00+00:00, funding_cycle_h=1, 24h_change=-22.60%, turnover=9036239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=1.154600, depth_time=2026-10-22T01:15:27+00:00, book20_bid_proxy_usdt=292845, book20_ask_proxy_usdt=354274, funding_indicative=-0.000124, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=17036564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=2.913000, depth_time=2026-10-22T01:15:28+00:00, book20_bid_proxy_usdt=1262432, book20_ask_proxy_usdt=889185, funding_indicative=0.000068, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=5748256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=8.729000, depth_time=2026-10-22T01:15:33+00:00, book20_bid_proxy_usdt=209647, book20_ask_proxy_usdt=169098, funding_indicative=0.000207, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=48599817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.001188, depth_time=2026-10-22T01:15:07+00:00, book20_bid_proxy_usdt=6043, book20_ask_proxy_usdt=14698, funding_indicative=-0.003925, next_funding_utc=2026-10-22T02:00:00+00:00, funding_cycle_h=1, 24h_change=-36.12%, turnover=15236103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.408300, depth_time=2026-10-22T01:15:41+00:00, book20_bid_proxy_usdt=608774, book20_ask_proxy_usdt=417787, funding_indicative=-0.000022, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=5167906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.129630, depth_time=2026-10-22T01:15:38+00:00, book20_bid_proxy_usdt=63746, book20_ask_proxy_usdt=46018, funding_indicative=-0.000011, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=6716142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.058270, depth_time=2026-10-22T01:15:17+00:00, book20_bid_proxy_usdt=510438, book20_ask_proxy_usdt=521760, funding_indicative=-0.000021, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.82%, turnover=24063178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T01:15:01+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=0.609800, depth_time=2026-10-22T01:15:22+00:00, book20_bid_proxy_usdt=238242, book20_ask_proxy_usdt=430269, funding_indicative=-0.000135, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=37879435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T01:15:02+00:00, last15m_closed_end=2026-10-22T01:15+00:00, prior8high=1.968900, depth_time=2026-10-22T01:15:18+00:00, book20_bid_proxy_usdt=41805, book20_ask_proxy_usdt=23928, funding_indicative=0.000035, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.76%, turnover=7337694. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
