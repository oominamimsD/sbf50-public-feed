# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T04:30:36Z**
- feed_generated_utc: 2026-10-23T04:30:38+00:00
- source_sha256: `bb424c947b1daa2d57559ded792fb1e9f44c0a078397a6a659eb0b7381927c70`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T04:30+00:00, close=81657.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004264|-7.46|114.81|-7.47|9075694|9.39|
|LIT_USDT|3.470000|-3.98|12.24|-3.99|10696238|0.29|
|SILVER_USDT|53.790000|-2.66|-5.86|-2.67|354745438|1.86|
|STRK_USDT|0.053080|-2.35|-44.91|-2.36|11837134|1.88|
|TIA_USDT|0.559900|-1.49|-7.07|-1.50|23087255|1.79|
|PUMPFUN_USDT|0.004619|-1.28|2.05|-1.29|38523041|2.17|
|ZEC_USDT|1218.510000|-1.27|3.28|-1.28|1894153786|0.08|
|PHA_USDT|0.061320|-1.17|21.37|-1.18|7800769|1.63|
|XAU_USDT|4015.190000|-1.09|-3.39|-1.10|737562097|0.03|
|XMR_USDT|606.370000|-1.06|11.47|-1.07|26676989|1.98|
|XAUT_USDT|4012.190000|-1.03|-3.20|-1.04|282813471|0.07|
|XPT_USDT|1570.720000|-1.01|-3.08|-1.02|5054029|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004264|0.004168|0.004261|1.17|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.470000|3.421300|3.470000|1.99|N|Y/Y|N/N|Y|N|
|PHA_USDT|0.061320|0.059190|0.061320|0.71|N|N/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004619|0.004599|0.004619|0.34|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.790000|53.870000|53.790000|0.38|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053080|0.052660|0.053080|0.52|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559900|0.558400|0.559900|1.09|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4012.190000|4015.390000|4012.190000|1.01|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4015.190000|4018.100000|4015.190000|1.05|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|606.370000|607.790000|606.370000|0.95|N|Y/Y|N/Y|Y|N|
|XPT_USDT|1570.720000|1572.010000|1570.720000|6.42|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1218.510000|1212.480000|1218.980000|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=0.004422, depth_time=2026-10-23T04:30:06+00:00, book20_bid_proxy_usdt=42597, book20_ask_proxy_usdt=27778, funding_indicative=0.000089, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.46%, turnover=9075694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T04:30:01+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=3.544400, depth_time=2026-10-23T04:30:11+00:00, book20_bid_proxy_usdt=28204, book20_ask_proxy_usdt=28921, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=10696238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=0.062580, depth_time=2026-10-23T04:30:25+00:00, book20_bid_proxy_usdt=76920, book20_ask_proxy_usdt=62160, funding_indicative=-0.000373, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=7800769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=0.004691, depth_time=2026-10-23T04:30:20+00:00, book20_bid_proxy_usdt=2859714, book20_ask_proxy_usdt=1401762, funding_indicative=0.000020, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=38523041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=54.410000, depth_time=2026-10-23T04:30:12+00:00, book20_bid_proxy_usdt=36099509, book20_ask_proxy_usdt=29654496, funding_indicative=0.000120, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=354745438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=0.053500, depth_time=2026-10-23T04:30:15+00:00, book20_bid_proxy_usdt=711214, book20_ask_proxy_usdt=636949, funding_indicative=0.000007, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=11837134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=0.566300, depth_time=2026-10-23T04:30:18+00:00, book20_bid_proxy_usdt=431012, book20_ask_proxy_usdt=340840, funding_indicative=0.000002, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=23087255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=4030.690000, depth_time=2026-10-23T04:30:33+00:00, book20_bid_proxy_usdt=170152, book20_ask_proxy_usdt=305184, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=282813471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=4032.600000, depth_time=2026-10-23T04:30:28+00:00, book20_bid_proxy_usdt=1180693, book20_ask_proxy_usdt=188262, funding_indicative=0.000083, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=737562097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=615.760000, depth_time=2026-10-23T04:30:30+00:00, book20_bid_proxy_usdt=11356, book20_ask_proxy_usdt=10147, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=26676989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPT_USDT: quote_utc=2026-10-23T04:30:01+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=1580.400000, depth_time=2026-10-23T04:30:35+00:00, book20_bid_proxy_usdt=79393, book20_ask_proxy_usdt=434549, funding_indicative=0.000000, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=5054029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T04:30:00+00:00, last15m_closed_end=2026-10-23T04:30+00:00, prior8high=1238.200000, depth_time=2026-10-23T04:30:23+00:00, book20_bid_proxy_usdt=710138, book20_ask_proxy_usdt=468498, funding_indicative=-0.000004, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=1894153786. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
