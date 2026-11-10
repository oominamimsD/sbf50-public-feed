# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T23:00:42Z**
- feed_generated_utc: 2026-11-10T23:00:44+00:00
- source_sha256: `0aa7589418d83c389c1984d3878d6fecfc62665e5fb4dee1407e21dc8017da21`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T23:00+00:00, close=73666.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T23:00+00:00, close=73666.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.193090|-23.05|43.58|-23.71|51897760|2.07|
|JCT_USDT|0.005199|-13.76|24.43|-14.42|19096629|1.93|
|PIEVERSE_USDT|1.844000|-10.21|56.88|-10.87|5423372|2.71|
|DASH_USDT|42.670000|-8.33|-7.52|-8.99|13716023|2.34|
|UNI_USDT|6.652000|-5.84|-9.53|-6.50|31090786|3.01|
|ZEC_USDT|1038.050000|-5.05|-13.76|-5.71|2195989864|0.29|
|NEAR_USDT|3.553000|-4.54|-7.92|-5.20|34360433|5.63|
|WLD_USDT|0.308100|-3.08|-17.19|-3.74|29611333|3.25|
|JUP_USDT|0.249600|-2.61|0.20|-3.27|5457958|4.01|
|ARB_USDT|0.161130|-2.38|0.78|-3.04|33439373|0.62|
|DOGE_USDT|0.067770|-2.33|-10.21|-2.99|90220315|1.48|
|ADA_USDT|0.173300|-2.25|-9.21|-2.91|22483144|5.77|
|LINK_USDT|10.287000|-2.12|-7.77|-2.78|89707459|0.97|
|HBAR_USDT|0.065550|-2.04|-6.39|-2.70|8666583|1.53|
|HYPE_USDT|72.246000|-1.85|-17.29|-2.51|40628303|0.14|
|BNB_USDT|678.460000|-1.61|-3.29|-2.27|7310810|0.15|
|QNT_USDT|181.450000|-0.89|-7.14|-1.55|46884379|0.55|
|AAVE_USDT|124.050000|-0.75|-3.42|-1.41|10259018|0.81|
|SILVER_USDT|51.630000|-0.74|3.30|-1.40|266586211|1.94|
|XRP_USDT|1.057700|-0.70|-17.41|-1.36|293216062|0.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.173300|0.173300|0.173300|0.32|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.161130|0.158140|0.161130|2.16|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.670000|42.750000|42.670000|0.13|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.067770|0.067520|0.067770|1.04|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065550|0.065690|0.065550|1.61|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|72.246000|72.127000|72.246000|0.50|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.193090|0.183240|0.196420|1.31|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005199|0.005119|0.005199|0.60|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.249600|0.249400|0.249600|0.15|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.287000|10.276000|10.287000|0.56|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.553000|3.538000|3.553000|0.30|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.844000|1.798500|1.844000|0.43|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.652000|6.662000|6.653000|0.60|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.308100|0.305700|0.308100|1.00|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1038.050000|1046.810000|1038.030000|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-10T23:00:02+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.175300, depth_time=2026-11-10T23:00:34+00:00, book20_bid_proxy_usdt=10020736, book20_ask_proxy_usdt=8093622, funding_indicative=-0.000084, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=22483144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.161100, depth_time=2026-11-10T23:00:27+00:00, book20_bid_proxy_usdt=50070, book20_ask_proxy_usdt=54375, funding_indicative=-0.000212, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=33439373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T23:00:02+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=43.460000, depth_time=2026-11-10T23:00:13+00:00, book20_bid_proxy_usdt=740548, book20_ask_proxy_usdt=583453, funding_indicative=-0.000175, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.33%, turnover=13716023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.068210, depth_time=2026-11-10T23:00:31+00:00, book20_bid_proxy_usdt=4435116, book20_ask_proxy_usdt=4231243, funding_indicative=-0.000046, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=90220315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T23:00:02+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.066260, depth_time=2026-11-10T23:00:38+00:00, book20_bid_proxy_usdt=787531, book20_ask_proxy_usdt=621001, funding_indicative=0.000022, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=8666583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=72.949000, depth_time=2026-11-10T23:00:40+00:00, book20_bid_proxy_usdt=72785, book20_ask_proxy_usdt=47112, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=40628303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.233780, depth_time=2026-11-10T23:00:07+00:00, book20_bid_proxy_usdt=3609, book20_ask_proxy_usdt=9514, funding_indicative=-0.017846, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=1, 24h_change=-23.05%, turnover=51897760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.005437, depth_time=2026-11-10T23:00:09+00:00, book20_bid_proxy_usdt=44383, book20_ask_proxy_usdt=36135, funding_indicative=0.000590, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.76%, turnover=19096629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T23:00:02+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.257600, depth_time=2026-11-10T23:00:26+00:00, book20_bid_proxy_usdt=597435, book20_ask_proxy_usdt=499788, funding_indicative=-0.000012, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=5457958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=10.378000, depth_time=2026-11-10T23:00:36+00:00, book20_bid_proxy_usdt=330571, book20_ask_proxy_usdt=420791, funding_indicative=0.000000, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=89707459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=3.611000, depth_time=2026-11-10T23:00:21+00:00, book20_bid_proxy_usdt=2984849, book20_ask_proxy_usdt=1851992, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.54%, turnover=34360433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=1.858500, depth_time=2026-11-10T23:00:07+00:00, book20_bid_proxy_usdt=21370, book20_ask_proxy_usdt=11749, funding_indicative=0.000058, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.21%, turnover=5423372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T23:00:02+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=6.769000, depth_time=2026-11-10T23:00:14+00:00, book20_bid_proxy_usdt=2220768, book20_ask_proxy_usdt=2881823, funding_indicative=-0.000021, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.84%, turnover=31090786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=0.311700, depth_time=2026-11-10T23:00:21+00:00, book20_bid_proxy_usdt=4957003, book20_ask_proxy_usdt=4453169, funding_indicative=-0.000081, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=29611333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T23:00:01+00:00, last15m_closed_end=2026-11-10T23:00+00:00, prior8high=1069.190000, depth_time=2026-11-10T23:00:19+00:00, book20_bid_proxy_usdt=174504, book20_ask_proxy_usdt=766564, funding_indicative=0.000011, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.05%, turnover=2195989864. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
