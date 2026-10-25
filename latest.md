# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T11:45:38Z**
- feed_generated_utc: 2026-10-25T11:45:41+00:00
- source_sha256: `64f48abd0ba916d0c4e9b35a0e4b9fce70b6ebc4b0ce51e3913a9c286422a72f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T11:45+00:00, close=80500.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T11:00+00:00, close=80246.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.046940|-30.35|51.66|-31.27|9675943|2.13|
|IRYS_USDT|0.033950|-26.27|166.06|-27.19|29412825|2.94|
|BTW_USDT|1.676500|-3.72|-26.12|-4.64|11437321|1.79|
|WLD_USDT|0.447600|-3.11|-9.68|-4.03|95033759|2.23|
|STRK_USDT|0.045300|-3.06|-31.51|-3.98|9473732|2.21|
|DOT_USDT|1.018800|-1.95|-8.82|-2.87|12340742|1.96|
|APT_USDT|0.693700|-1.16|-13.01|-2.08|6069079|1.44|
|SUI_USDT|0.914900|-1.09|-6.81|-2.01|68395326|1.09|
|PENGU_USDT|0.007376|-0.90|-1.03|-1.82|5854397|1.36|
|SEI_USDT|0.052510|-0.69|-15.32|-1.61|7842787|1.91|
|ARB_USDT|0.164840|-0.54|-10.37|-1.46|16025568|0.61|
|AGT_USDT|0.066720|-0.31|-7.40|-1.23|5107763|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066720|0.064730|0.066730|2.13|N|Y/Y|N/N|Y|N|
|APT_USDT|0.693700|0.690000|0.693700|2.10|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164840|0.163810|0.164840|0.73|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.676500|1.610600|1.676500|0.52|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.018800|1.013200|1.018900|0.59|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033950|0.034380|0.033940|1.18|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.046940|0.046940|0.046820|1.30|Y|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007376|0.007333|0.007376|3.05|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052510|0.052190|0.052520|1.72|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045300|0.044920|0.045300|2.11|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.914900|0.907000|0.915100|0.93|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.447600|0.441100|0.447700|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.071720, depth_time=2026-10-25T11:45:37+00:00, book20_bid_proxy_usdt=9616, book20_ask_proxy_usdt=12875, funding_indicative=0.000151, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.31%, turnover=5107763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.695500, depth_time=2026-10-25T11:45:24+00:00, book20_bid_proxy_usdt=105890, book20_ask_proxy_usdt=129080, funding_indicative=-0.000129, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=6069079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.165000, depth_time=2026-10-25T11:45:34+00:00, book20_bid_proxy_usdt=91779, book20_ask_proxy_usdt=132612, funding_indicative=0.000062, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.54%, turnover=16025568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=1.695000, depth_time=2026-10-25T11:45:14+00:00, book20_bid_proxy_usdt=13068, book20_ask_proxy_usdt=110865, funding_indicative=-0.016389, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.72%, turnover=11437321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=1.026000, depth_time=2026-10-25T11:45:21+00:00, book20_bid_proxy_usdt=228719, book20_ask_proxy_usdt=336763, funding_indicative=-0.000070, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=12340742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.036110, depth_time=2026-10-25T11:45:11+00:00, book20_bid_proxy_usdt=146613, book20_ask_proxy_usdt=52109, funding_indicative=-0.000434, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=1, 24h_change=-26.27%, turnover=29412825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.053130, depth_time=2026-10-25T11:45:09+00:00, book20_bid_proxy_usdt=63823, book20_ask_proxy_usdt=91356, funding_indicative=-0.001606, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=1, 24h_change=-30.35%, turnover=9675943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.007401, depth_time=2026-10-25T11:45:27+00:00, book20_bid_proxy_usdt=143206, book20_ask_proxy_usdt=174490, funding_indicative=-0.000082, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=5854397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.052560, depth_time=2026-10-25T11:45:32+00:00, book20_bid_proxy_usdt=217601, book20_ask_proxy_usdt=463542, funding_indicative=-0.000117, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.69%, turnover=7842787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.045550, depth_time=2026-10-25T11:45:19+00:00, book20_bid_proxy_usdt=645834, book20_ask_proxy_usdt=938493, funding_indicative=0.000036, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=9473732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.914500, depth_time=2026-10-25T11:45:27+00:00, book20_bid_proxy_usdt=837938, book20_ask_proxy_usdt=1262195, funding_indicative=-0.000010, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=68395326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T11:45:01+00:00, last15m_closed_end=2026-10-25T11:45+00:00, prior8high=0.448500, depth_time=2026-10-25T11:45:16+00:00, book20_bid_proxy_usdt=1606635, book20_ask_proxy_usdt=1839748, funding_indicative=-0.000007, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=95033759. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
