# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T14:00:45Z**
- feed_generated_utc: 2026-10-30T14:00:48+00:00
- source_sha256: `c2bfcde3060d7a3b0bc9ec1c126d1b16380d76d16e928acfd480c57409611a85`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T14:00+00:00, close=77144.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T14:00+00:00, close=77144.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.258000|-23.20|-29.72|-17.54|10115213|0.79|
|TIA_USDT|0.457500|-16.69|-19.51|-11.03|19130704|2.19|
|CRV_USDT|0.282600|-14.59|-23.06|-8.93|9337775|3.54|
|LIT_USDT|2.802800|-13.94|-22.45|-8.28|14999199|0.36|
|FARTCOIN_USDT|0.118080|-12.14|-17.33|-6.48|15390941|0.85|
|FET_USDT|0.163000|-11.79|-12.03|-6.13|13937348|6.14|
|ETHFI_USDT|0.599500|-11.77|-9.48|-6.11|6043498|1.67|
|PENGU_USDT|0.007198|-11.47|-6.85|-5.81|10301570|1.39|
|PUMPFUN_USDT|0.004026|-11.02|-13.95|-5.36|29334289|2.48|
|INJ_USDT|7.145000|-10.75|-9.92|-5.09|33329462|1.40|
|LDO_USDT|0.332600|-10.73|-13.04|-5.07|6465293|3.01|
|TAO_USDT|232.180000|-10.27|-9.88|-4.61|86707917|1.29|
|SEI_USDT|0.048050|-10.08|-17.25|-4.42|7125180|2.08|
|RENDER_USDT|1.545000|-9.54|-14.92|-3.88|5024882|6.47|
|ONDO_USDT|0.390400|-9.16|-9.41|-3.50|33005768|2.56|
|ZEC_USDT|1233.200000|-9.14|-0.08|-3.48|2145554747|0.08|
|JUP_USDT|0.253500|-7.81|-18.22|-2.15|6835858|3.95|
|ADA_USDT|0.191300|-7.31|-10.56|-1.65|68229380|5.23|
|AVAX_USDT|8.250000|-7.26|-9.99|-1.60|37955283|1.21|
|SOL_USDT|95.190000|-7.25|-8.97|-1.59|873147530|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.258000|1.223900|1.254700|1.34|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.282600|0.280400|0.282600|1.32|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.599500|0.597600|0.600400|6.31|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118080|0.116890|0.118190|3.78|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163000|0.162300|0.163300|4.88|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.145000|7.061000|7.145000|5.79|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.332600|0.328800|0.332600|1.99|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.802800|2.728500|2.806800|1.13|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.390400|0.387200|0.390800|1.29|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007198|0.007137|0.007203|1.06|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004026|0.003994|0.004031|7.26|N|Y/Y|Y/Y|Y|N|
|RENDER_USDT|1.545000|1.537000|1.547000|4.55|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048050|0.047870|0.048170|3.78|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|232.180000|230.330000|232.420000|2.53|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.457500|0.453400|0.458500|1.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=1.358500, depth_time=2026-10-30T14:00:08+00:00, book20_bid_proxy_usdt=9818, book20_ask_proxy_usdt=21438, funding_indicative=-0.000081, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.20%, turnover=10115213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.288300, depth_time=2026-10-30T14:00:10+00:00, book20_bid_proxy_usdt=531708, book20_ask_proxy_usdt=271626, funding_indicative=-0.000147, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.59%, turnover=9337775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.610600, depth_time=2026-10-30T14:00:24+00:00, book20_bid_proxy_usdt=192028, book20_ask_proxy_usdt=122439, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.77%, turnover=6043498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.118760, depth_time=2026-10-30T14:00:19+00:00, book20_bid_proxy_usdt=43718, book20_ask_proxy_usdt=44017, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.14%, turnover=15390941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.165500, depth_time=2026-10-30T14:00:21+00:00, book20_bid_proxy_usdt=935240, book20_ask_proxy_usdt=662488, funding_indicative=0.000087, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.79%, turnover=13937348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=7.294000, depth_time=2026-10-30T14:00:31+00:00, book20_bid_proxy_usdt=217644, book20_ask_proxy_usdt=177769, funding_indicative=0.000106, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.75%, turnover=33329462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.336400, depth_time=2026-10-30T14:00:33+00:00, book20_bid_proxy_usdt=1244943, book20_ask_proxy_usdt=661475, funding_indicative=0.000080, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.73%, turnover=6465293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=2.828700, depth_time=2026-10-30T14:00:16+00:00, book20_bid_proxy_usdt=21789, book20_ask_proxy_usdt=20873, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.94%, turnover=14999199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.392700, depth_time=2026-10-30T14:00:44+00:00, book20_bid_proxy_usdt=861075, book20_ask_proxy_usdt=1291626, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.16%, turnover=33005768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.007315, depth_time=2026-10-30T14:00:26+00:00, book20_bid_proxy_usdt=99634, book20_ask_proxy_usdt=55523, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.47%, turnover=10301570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.004101, depth_time=2026-10-30T14:00:29+00:00, book20_bid_proxy_usdt=1163508, book20_ask_proxy_usdt=921766, funding_indicative=0.000012, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.02%, turnover=29334289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=1.574000, depth_time=2026-10-30T14:00:41+00:00, book20_bid_proxy_usdt=1567686, book20_ask_proxy_usdt=1114836, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.54%, turnover=5024882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.048920, depth_time=2026-10-30T14:00:39+00:00, book20_bid_proxy_usdt=105186, book20_ask_proxy_usdt=169735, funding_indicative=0.000074, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.08%, turnover=7125180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=234.090000, depth_time=2026-10-30T14:00:36+00:00, book20_bid_proxy_usdt=53524, book20_ask_proxy_usdt=25345, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.27%, turnover=86707917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T14:00:04+00:00, last15m_closed_end=2026-10-30T14:00+00:00, prior8high=0.466600, depth_time=2026-10-30T14:00:11+00:00, book20_bid_proxy_usdt=245400, book20_ask_proxy_usdt=85252, funding_indicative=0.000004, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.69%, turnover=19130704. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
