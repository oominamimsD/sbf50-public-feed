# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T01:30:37Z**
- feed_generated_utc: 2026-10-23T01:30:39+00:00
- source_sha256: `964dc4ba00758a489c004133bb49da6050dcf003b2282e91e16688f8735dcc8c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T01:30+00:00, close=81448.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T01:00+00:00, close=81431.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.436400|-4.91|11.15|-4.67|12829672|0.29|
|JCT_USDT|0.004392|-4.68|121.25|-4.44|9606873|6.83|
|PHA_USDT|0.059900|-3.46|18.56|-3.22|8327305|1.67|
|STRK_USDT|0.052830|-2.81|-45.17|-2.57|12543072|1.89|
|TIA_USDT|0.556800|-2.04|-7.58|-1.80|23223828|1.80|
|ARB_USDT|0.180190|-1.87|-5.13|-1.63|31734256|0.56|
|XPL_USDT|0.076110|-1.79|-10.18|-1.55|5824918|1.31|
|APT_USDT|0.759400|-1.65|-8.14|-1.41|9349886|1.32|
|SILVER_USDT|54.380000|-1.59|-4.83|-1.35|375113314|1.84|
|SEI_USDT|0.057240|-1.42|-6.86|-1.18|9768041|1.75|
|XMR_USDT|604.660000|-1.34|11.15|-1.10|27542281|0.50|
|PUMPFUN_USDT|0.004619|-1.28|2.05|-1.04|37016201|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.759400|0.748700|0.759400|2.01|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.180190|0.178040|0.180190|0.48|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004392|0.004411|0.004392|0.65|N|N/N|N/N|Y|N|
|LIT_USDT|3.436400|3.363100|3.436400|0.53|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.059900|0.059950|0.059890|0.55|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004619|0.004529|0.004619|0.61|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057240|0.056780|0.057270|2.93|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.380000|54.240000|54.360000|4.48|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052830|0.052330|0.052830|0.82|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.556800|0.555700|0.556900|1.00|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|604.660000|593.340000|604.620000|0.80|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.076110|0.075130|0.076140|2.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.765000, depth_time=2026-10-23T01:30:26+00:00, book20_bid_proxy_usdt=166284, book20_ask_proxy_usdt=126329, funding_indicative=-0.000058, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=9349886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.181100, depth_time=2026-10-23T01:30:21+00:00, book20_bid_proxy_usdt=72775, book20_ask_proxy_usdt=75088, funding_indicative=-0.000118, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=31734256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T01:30:01+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.004606, depth_time=2026-10-23T01:30:09+00:00, book20_bid_proxy_usdt=35455, book20_ask_proxy_usdt=64823, funding_indicative=0.000098, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=9606873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=3.439300, depth_time=2026-10-23T01:30:08+00:00, book20_bid_proxy_usdt=26173, book20_ask_proxy_usdt=17140, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=12829672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.061510, depth_time=2026-10-23T01:30:13+00:00, book20_bid_proxy_usdt=81950, book20_ask_proxy_usdt=77632, funding_indicative=-0.000596, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=8327305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.004620, depth_time=2026-10-23T01:30:36+00:00, book20_bid_proxy_usdt=1620386, book20_ask_proxy_usdt=687183, funding_indicative=0.000019, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=37016201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.057380, depth_time=2026-10-23T01:30:31+00:00, book20_bid_proxy_usdt=232785, book20_ask_proxy_usdt=492088, funding_indicative=-0.000005, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=9768041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T01:30:01+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=54.870000, depth_time=2026-10-23T01:30:28+00:00, book20_bid_proxy_usdt=31801786, book20_ask_proxy_usdt=31657436, funding_indicative=0.000147, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=375113314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.053350, depth_time=2026-10-23T01:30:16+00:00, book20_bid_proxy_usdt=671606, book20_ask_proxy_usdt=571500, funding_indicative=0.000040, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=12543072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.560500, depth_time=2026-10-23T01:30:18+00:00, book20_bid_proxy_usdt=322970, book20_ask_proxy_usdt=344594, funding_indicative=-0.000010, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=23223828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=603.670000, depth_time=2026-10-23T01:30:32+00:00, book20_bid_proxy_usdt=30517, book20_ask_proxy_usdt=5209, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=27542281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T01:30:02+00:00, last15m_closed_end=2026-10-23T01:30+00:00, prior8high=0.076230, depth_time=2026-10-23T01:30:24+00:00, book20_bid_proxy_usdt=355191, book20_ask_proxy_usdt=528672, funding_indicative=0.000008, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=5824918. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
