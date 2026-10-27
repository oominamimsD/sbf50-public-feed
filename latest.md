# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T14:15:47Z**
- feed_generated_utc: 2026-10-27T14:15:51+00:00
- source_sha256: `f9207d8729f222b8c633ed156f1f720011cb7cee34b591fb0484d884136ff62b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T14:15+00:00, close=80099.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T14:00+00:00, close=80014.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025210|-8.59|105.29|-8.22|6476346|3.96|
|QNT_USDT|197.870000|-5.90|1.10|-5.53|97475964|3.54|
|AAVE_USDT|131.170000|-4.06|-10.90|-3.69|27408454|0.76|
|WLD_USDT|0.428200|-3.77|-15.42|-3.40|71476938|2.34|
|DOT_USDT|0.985200|-3.65|-14.09|-3.28|11164048|1.02|
|FILECOIN_USDT|0.889200|-3.42|-12.13|-3.05|5878801|1.12|
|PUMPFUN_USDT|0.004196|-3.04|-5.83|-2.67|21151051|2.38|
|ICP_USDT|2.573000|-2.16|-9.81|-1.79|5298055|3.89|
|AVAX_USDT|8.806000|-2.12|-7.90|-1.75|23547019|1.14|
|TIA_USDT|0.524400|-2.10|-13.82|-1.73|17373769|1.91|
|HBAR_USDT|0.075910|-1.87|-7.27|-1.50|9638417|1.32|
|TAO_USDT|249.200000|-1.70|-7.11|-1.33|51276301|1.20|
|LINK_USDT|11.349000|-1.55|-4.97|-1.18|129789566|4.41|
|SOL_USDT|100.310000|-1.50|-3.63|-1.13|692734690|1.00|
|ARB_USDT|0.167530|-1.44|-14.36|-1.07|16878333|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.170000|130.520000|131.170000|0.95|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167530|0.166210|0.167530|0.75|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.806000|8.732000|8.806000|1.36|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.985200|0.982200|0.985200|3.06|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.889200|0.885000|0.889200|2.60|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075910|0.075590|0.075910|1.40|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.573000|2.560000|2.574000|2.96|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025210|0.024590|0.025210|0.84|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.349000|11.274000|11.349000|1.45|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004196|0.004133|0.004196|1.65|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.870000|196.750000|197.870000|0.78|N|Y/Y|N/N|Y|N|
|SOL_USDT|100.310000|99.900000|100.310000|2.13|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.200000|247.220000|249.200000|0.57|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.524400|0.519900|0.524400|0.94|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.428200|0.425200|0.428200|2.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=133.100000, depth_time=2026-10-27T14:15:13+00:00, book20_bid_proxy_usdt=353752, book20_ask_proxy_usdt=353627, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=27408454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.169600, depth_time=2026-10-27T14:15:47+00:00, book20_bid_proxy_usdt=60051, book20_ask_proxy_usdt=83340, funding_indicative=0.000011, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=16878333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=8.864000, depth_time=2026-10-27T14:15:29+00:00, book20_bid_proxy_usdt=1042223, book20_ask_proxy_usdt=1296769, funding_indicative=0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=23547019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.996900, depth_time=2026-10-27T14:15:19+00:00, book20_bid_proxy_usdt=318891, book20_ask_proxy_usdt=482764, funding_indicative=-0.000203, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=11164048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.902000, depth_time=2026-10-27T14:15:21+00:00, book20_bid_proxy_usdt=1049600, book20_ask_proxy_usdt=1550045, funding_indicative=0.000030, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=5878801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.076600, depth_time=2026-10-27T14:15:34+00:00, book20_bid_proxy_usdt=1157179, book20_ask_proxy_usdt=1049843, funding_indicative=0.000073, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=9638417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=2.608000, depth_time=2026-10-27T14:15:27+00:00, book20_bid_proxy_usdt=1055684, book20_ask_proxy_usdt=1137662, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=5298055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.025210, depth_time=2026-10-27T14:15:08+00:00, book20_bid_proxy_usdt=121209, book20_ask_proxy_usdt=89235, funding_indicative=-0.000231, next_funding_utc=2026-10-27T15:00:00+00:00, funding_cycle_h=1, 24h_change=-8.59%, turnover=6476346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=11.453000, depth_time=2026-10-27T14:15:41+00:00, book20_bid_proxy_usdt=562332, book20_ask_proxy_usdt=465915, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=129789566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.004256, depth_time=2026-10-27T14:15:24+00:00, book20_bid_proxy_usdt=1744666, book20_ask_proxy_usdt=1345038, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=21151051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=203.620000, depth_time=2026-10-27T14:15:11+00:00, book20_bid_proxy_usdt=58635, book20_ask_proxy_usdt=50651, funding_indicative=-0.000217, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.90%, turnover=97475964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=101.160000, depth_time=2026-10-27T14:15:44+00:00, book20_bid_proxy_usdt=14911109, book20_ask_proxy_usdt=14997495, funding_indicative=0.000082, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=692734690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=251.610000, depth_time=2026-10-27T14:15:39+00:00, book20_bid_proxy_usdt=164406, book20_ask_proxy_usdt=116005, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.70%, turnover=51276301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.531400, depth_time=2026-10-27T14:15:33+00:00, book20_bid_proxy_usdt=407892, book20_ask_proxy_usdt=406555, funding_indicative=0.000005, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=17373769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T14:15:00+00:00, last15m_closed_end=2026-10-27T14:15+00:00, prior8high=0.438400, depth_time=2026-10-27T14:15:16+00:00, book20_bid_proxy_usdt=3309754, book20_ask_proxy_usdt=4222733, funding_indicative=-0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=71476938. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
