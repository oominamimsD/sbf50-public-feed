# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T09:45:43Z**
- feed_generated_utc: 2026-10-27T09:45:47+00:00
- source_sha256: `c67a761215fd4dbeda40ea1515203209d5d43f92fd83e3ab503bb60defb6403c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T09:45+00:00, close=79666.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T09:00+00:00, close=79834.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.100390|-32.67|39.39|-31.76|12039082|9.96|
|IRYS_USDT|0.025780|-6.52|109.93|-5.61|7642039|3.88|
|PUMPFUN_USDT|0.004106|-5.12|-7.85|-4.21|21673740|2.44|
|ENA_USDT|0.199730|-5.05|6.28|-4.14|86944494|0.50|
|AAVE_USDT|130.150000|-4.81|-11.59|-3.90|25562600|0.77|
|DOT_USDT|0.982700|-3.90|-14.30|-2.99|10827091|2.04|
|FILECOIN_USDT|0.888600|-3.48|-12.19|-2.57|5962719|1.12|
|ONDO_USDT|0.404700|-3.36|-6.44|-2.45|23353692|2.47|
|NEAR_USDT|4.426000|-3.21|-9.74|-2.30|92117103|2.26|
|WLD_USDT|0.431400|-3.05|-14.79|-2.14|67164696|4.64|
|AVAX_USDT|8.730000|-2.96|-8.70|-2.05|29515303|1.15|
|ARB_USDT|0.165060|-2.90|-15.62|-1.99|20332592|0.60|
|TAO_USDT|246.230000|-2.87|-8.22|-1.96|46177486|3.25|
|TIA_USDT|0.521500|-2.65|-14.29|-1.74|17373462|3.84|
|INJ_USDT|7.734000|-2.52|-9.55|-1.61|22409204|1.29|
|QNT_USDT|205.510000|-2.26|5.01|-1.35|131589111|4.87|
|LINK_USDT|11.276000|-2.18|-5.58|-1.27|122910032|1.77|
|SOL_USDT|99.630000|-2.17|-4.28|-1.26|671575592|1.00|
|HBAR_USDT|0.075690|-2.15|-7.54|-1.24|10209431|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.150000|130.500000|130.120000|4.43|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.165060|0.166340|0.165060|6.41|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.730000|8.753000|8.727000|0.85|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.100390|0.108110|0.100800|2.77|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.982700|0.988200|0.982200|1.96|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.199730|0.201150|0.199740|3.64|Y|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.888600|0.893200|0.888600|12.48|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.734000|7.749000|7.734000|1.14|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.025780|0.025430|0.025790|0.85|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.426000|4.417000|4.426000|1.26|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.404700|0.405800|0.404700|1.39|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004106|0.004113|0.004106|2.44|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|246.230000|247.110000|246.060000|4.73|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.521500|0.524500|0.521500|3.27|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.431400|0.432800|0.431200|4.33|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=132.300000, depth_time=2026-10-27T09:45:17+00:00, book20_bid_proxy_usdt=1113035, book20_ask_proxy_usdt=465846, funding_indicative=0.000096, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.81%, turnover=25562600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.168680, depth_time=2026-10-27T09:45:34+00:00, book20_bid_proxy_usdt=48854, book20_ask_proxy_usdt=75524, funding_indicative=-0.000002, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=20332592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=8.828000, depth_time=2026-10-27T09:45:31+00:00, book20_bid_proxy_usdt=1501152, book20_ask_proxy_usdt=1703226, funding_indicative=-0.000028, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=29515303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.133100, depth_time=2026-10-27T09:45:08+00:00, book20_bid_proxy_usdt=8018, book20_ask_proxy_usdt=16030, funding_indicative=-0.000815, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-32.67%, turnover=12039082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=1.001200, depth_time=2026-10-27T09:45:17+00:00, book20_bid_proxy_usdt=417641, book20_ask_proxy_usdt=414411, funding_indicative=-0.000086, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=10827091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.208980, depth_time=2026-10-27T09:45:15+00:00, book20_bid_proxy_usdt=90698, book20_ask_proxy_usdt=191411, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.05%, turnover=86944494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T09:45:04+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.903000, depth_time=2026-10-27T09:45:20+00:00, book20_bid_proxy_usdt=1210134, book20_ask_proxy_usdt=1607558, funding_indicative=0.000028, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=5962719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=7.851000, depth_time=2026-10-27T09:45:42+00:00, book20_bid_proxy_usdt=489204, book20_ask_proxy_usdt=225909, funding_indicative=0.000194, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=22409204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.027080, depth_time=2026-10-27T09:45:10+00:00, book20_bid_proxy_usdt=65969, book20_ask_proxy_usdt=107423, funding_indicative=-0.000273, next_funding_utc=2026-10-27T10:00:00+00:00, funding_cycle_h=1, 24h_change=-6.52%, turnover=7642039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=4.488000, depth_time=2026-10-27T09:45:26+00:00, book20_bid_proxy_usdt=4162238, book20_ask_proxy_usdt=4003284, funding_indicative=0.000076, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=92117103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.411600, depth_time=2026-10-27T09:45:24+00:00, book20_bid_proxy_usdt=3372584, book20_ask_proxy_usdt=3909604, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=23353692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.004216, depth_time=2026-10-27T09:45:12+00:00, book20_bid_proxy_usdt=1968864, book20_ask_proxy_usdt=2223748, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.12%, turnover=21673740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=250.230000, depth_time=2026-10-27T09:45:37+00:00, book20_bid_proxy_usdt=150966, book20_ask_proxy_usdt=143410, funding_indicative=0.000042, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=46177486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.533400, depth_time=2026-10-27T09:45:38+00:00, book20_bid_proxy_usdt=394291, book20_ask_proxy_usdt=495346, funding_indicative=-0.000002, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=17373462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T09:45:03+00:00, last15m_closed_end=2026-10-27T09:45+00:00, prior8high=0.439800, depth_time=2026-10-27T09:45:30+00:00, book20_bid_proxy_usdt=3693137, book20_ask_proxy_usdt=3846414, funding_indicative=-0.000181, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=67164696. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
