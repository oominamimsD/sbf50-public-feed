# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T21:00:37Z**
- feed_generated_utc: 2026-11-07T21:00:39+00:00
- source_sha256: `e01e935a424fc6cb72d5c38d10ebd117170d70dcb67c4bca5c1239f6e8dc4603`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T21:00+00:00, close=75657.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T21:00+00:00, close=75657.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.122500|-3.39|-60.57|-3.30|11147189|8.18|
|PUMPFUN_USDT|0.003653|-2.37|-12.64|-2.28|18287181|2.74|
|ENA_USDT|0.156770|-2.17|-19.19|-2.08|27095431|0.64|
|WLD_USDT|0.330000|-1.90|-18.39|-1.81|25204266|3.03|
|AAVE_USDT|129.810000|-1.83|-4.20|-1.74|8388363|0.77|
|PEPE_USDT|0.000005|-1.54|-2.62|-1.45|43737291|0.62|
|LINK_USDT|10.747000|-1.44|-7.12|-1.35|70371265|0.93|
|DOT_USDT|0.888800|-1.28|-7.32|-1.19|5497487|1.13|
|ADA_USDT|0.180300|-1.25|-6.86|-1.16|12740752|5.54|
|NEAR_USDT|3.636000|-1.16|-18.76|-1.07|23585770|5.50|
|TIA_USDT|0.436000|-1.13|-11.03|-1.04|6343595|6.89|
|AVAX_USDT|8.160000|-1.12|-4.39|-1.03|8290369|1.23|
|TRUMPOFFICIAL_USDT|1.175000|-1.09|-25.77|-1.00|5052439|8.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.810000|130.350000|129.870000|1.70|Y|Y/Y|N/N|Y|N|
|ADA_USDT|0.180300|0.180700|0.180300|17.35|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.160000|8.186000|8.160000|5.12|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.888800|0.895800|0.888800|12.06|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.156770|0.156440|0.156800|2.07|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.747000|10.783000|10.747000|3.77|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|3.636000|3.640000|3.636000|7.48|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|1.37|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003653|0.003671|0.003653|1.30|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.436000|0.438200|0.436000|4.01|Y|Y/N|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.175000|1.176000|1.175000|12.06|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.122500|0.121100|0.122500|0.34|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.330000|0.332000|0.330000|7.52|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=132.160000, depth_time=2026-11-07T21:00:17+00:00, book20_bid_proxy_usdt=584639, book20_ask_proxy_usdt=302304, funding_indicative=0.000042, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=8388363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.182400, depth_time=2026-11-07T21:00:26+00:00, book20_bid_proxy_usdt=9446267, book20_ask_proxy_usdt=10332315, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=12740752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=8.254000, depth_time=2026-11-07T21:00:33+00:00, book20_bid_proxy_usdt=1051917, book20_ask_proxy_usdt=1500286, funding_indicative=0.000098, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=8290369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.902300, depth_time=2026-11-07T21:00:23+00:00, book20_bid_proxy_usdt=291343, book20_ask_proxy_usdt=471650, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=5497487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.158990, depth_time=2026-11-07T21:00:12+00:00, book20_bid_proxy_usdt=156402, book20_ask_proxy_usdt=84948, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=27095431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=10.903000, depth_time=2026-11-07T21:00:21+00:00, book20_bid_proxy_usdt=501444, book20_ask_proxy_usdt=287248, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=70371265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=3.684000, depth_time=2026-11-07T21:00:29+00:00, book20_bid_proxy_usdt=3316386, book20_ask_proxy_usdt=4321642, funding_indicative=0.000048, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=23585770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.000005, depth_time=2026-11-07T21:00:19+00:00, book20_bid_proxy_usdt=23972, book20_ask_proxy_usdt=41437, funding_indicative=0.000047, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=43737291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.003738, depth_time=2026-11-07T21:00:08+00:00, book20_bid_proxy_usdt=1938294, book20_ask_proxy_usdt=2572618, funding_indicative=-0.000011, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=18287181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.447300, depth_time=2026-11-07T21:00:31+00:00, book20_bid_proxy_usdt=297612, book20_ask_proxy_usdt=365274, funding_indicative=0.000003, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=6343595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=1.194000, depth_time=2026-11-07T21:00:34+00:00, book20_bid_proxy_usdt=1794562, book20_ask_proxy_usdt=1693348, funding_indicative=-0.000106, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=5052439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.125000, depth_time=2026-11-07T21:00:07+00:00, book20_bid_proxy_usdt=205691, book20_ask_proxy_usdt=181005, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=11147189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T21:00:02+00:00, last15m_closed_end=2026-11-07T21:00+00:00, prior8high=0.336900, depth_time=2026-11-07T21:00:14+00:00, book20_bid_proxy_usdt=3095110, book20_ask_proxy_usdt=4877250, funding_indicative=-0.000232, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=25204266. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
