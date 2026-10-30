# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T05:00:41Z**
- feed_generated_utc: 2026-10-30T05:00:46+00:00
- source_sha256: `7e87aa7dc8b6a0aa1041c258049fc9cd078a592c06e1e65940b3a3282e5dd7cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T05:00+00:00, close=78237, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T05:00+00:00, close=78237, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.269800|-18.46|-26.54|-14.19|7945538|3.71|
|TIA_USDT|0.457000|-16.78|-19.59|-12.51|18787855|2.19|
|PYTH_USDT|0.061230|-16.34|-17.45|-12.07|5212159|3.27|
|LDO_USDT|0.323900|-13.07|-15.32|-8.80|6359490|3.09|
|FET_USDT|0.161700|-11.78|-12.73|-7.51|13958158|6.19|
|OP_USDT|0.101240|-11.12|-15.52|-6.85|9028246|1.98|
|BTW_USDT|1.472500|-10.10|-17.73|-5.83|11297197|4.08|
|WLD_USDT|0.392300|-10.08|-26.27|-5.81|89239414|2.55|
|ETHFI_USDT|0.611400|-10.02|-7.68|-5.75|5904980|1.64|
|APT_USDT|0.619900|-9.72|-19.72|-5.45|12776000|3.23|
|PUMPFUN_USDT|0.004091|-9.59|-12.56|-5.32|30934484|2.44|
|JUP_USDT|0.254800|-9.58|-17.80|-5.31|6633361|3.92|
|INJ_USDT|7.359000|-9.50|-7.22|-5.23|30656044|1.36|
|FARTCOIN_USDT|0.118730|-9.26|-16.87|-4.99|15045316|0.84|
|PENGU_USDT|0.007163|-8.94|-7.31|-4.67|9977541|1.40|
|STRK_USDT|0.043010|-8.78|-20.87|-4.51|6745722|2.33|
|TRUMPOFFICIAL_USDT|1.558000|-8.62|-10.66|-4.35|10961339|6.42|
|SEI_USDT|0.048340|-7.78|-16.75|-3.51|7171760|2.07|
|SHIB_USDT|0.000005|-7.03|-6.21|-2.76|7864603|2.14|
|DASH_USDT|48.020000|-6.73|-4.49|-2.46|25809677|2.08|
|JASMY_USDT|0.003714|-6.02|-18.48|-1.75|6266979|2.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.619900|0.601500|0.619900|1.19|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.472500|1.458400|1.472300|2.60|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.269800|0.270100|0.269800|3.75|Y|Y/Y|Y/Y|Y|Y|
|ETHFI_USDT|0.611400|0.577100|0.611700|0.95|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118730|0.114070|0.118730|0.46|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161700|0.155000|0.161700|0.37|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.359000|7.048000|7.359000|1.05|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.254800|0.246600|0.254800|1.60|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.323900|0.313800|0.323900|0.13|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.101240|0.097010|0.101250|0.84|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007163|0.006841|0.007163|0.44|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004091|0.003903|0.004093|0.56|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061230|0.059290|0.061240|0.29|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.457000|0.456800|0.457200|0.68|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.392300|0.377300|0.392400|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.618800, depth_time=2026-10-30T05:00:28+00:00, book20_bid_proxy_usdt=76684, book20_ask_proxy_usdt=135971, funding_indicative=-0.000192, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.72%, turnover=12776000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=1.518200, depth_time=2026-10-30T05:00:23+00:00, book20_bid_proxy_usdt=17203, book20_ask_proxy_usdt=11974, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.10%, turnover=11297197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.277500, depth_time=2026-10-30T05:00:08+00:00, book20_bid_proxy_usdt=388222, book20_ask_proxy_usdt=416062, funding_indicative=0.000058, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-18.46%, turnover=7945538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.608100, depth_time=2026-10-30T05:00:27+00:00, book20_bid_proxy_usdt=219165, book20_ask_proxy_usdt=192966, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.02%, turnover=5904980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.118990, depth_time=2026-10-30T05:00:38+00:00, book20_bid_proxy_usdt=71945, book20_ask_proxy_usdt=44326, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.26%, turnover=15045316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.161200, depth_time=2026-10-30T05:00:17+00:00, book20_bid_proxy_usdt=999883, book20_ask_proxy_usdt=682905, funding_indicative=-0.000635, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.78%, turnover=13958158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T05:00:02+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=7.380000, depth_time=2026-10-30T05:00:36+00:00, book20_bid_proxy_usdt=150814, book20_ask_proxy_usdt=134437, funding_indicative=-0.000085, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.50%, turnover=30656044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.254000, depth_time=2026-10-30T05:00:33+00:00, book20_bid_proxy_usdt=427314, book20_ask_proxy_usdt=422020, funding_indicative=-0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.58%, turnover=6633361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.323200, depth_time=2026-10-30T05:00:13+00:00, book20_bid_proxy_usdt=554104, book20_ask_proxy_usdt=293055, funding_indicative=0.000094, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.07%, turnover=6359490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.100840, depth_time=2026-10-30T05:00:20+00:00, book20_bid_proxy_usdt=47700, book20_ask_proxy_usdt=84034, funding_indicative=-0.000292, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.12%, turnover=9028246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.007172, depth_time=2026-10-30T05:00:40+00:00, book20_bid_proxy_usdt=60126, book20_ask_proxy_usdt=58725, funding_indicative=-0.000005, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.94%, turnover=9977541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.004065, depth_time=2026-10-30T05:00:32+00:00, book20_bid_proxy_usdt=1153464, book20_ask_proxy_usdt=1037040, funding_indicative=-0.000026, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.59%, turnover=30934484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.061230, depth_time=2026-10-30T05:00:13+00:00, book20_bid_proxy_usdt=106922, book20_ask_proxy_usdt=285034, funding_indicative=-0.000118, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.34%, turnover=5212159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T05:00:03+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.466000, depth_time=2026-10-30T05:00:11+00:00, book20_bid_proxy_usdt=207949, book20_ask_proxy_usdt=252382, funding_indicative=0.000003, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.78%, turnover=18787855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-30T05:00:02+00:00, last15m_closed_end=2026-10-30T05:00+00:00, prior8high=0.389800, depth_time=2026-10-30T05:00:25+00:00, book20_bid_proxy_usdt=2235914, book20_ask_proxy_usdt=1888953, funding_indicative=0.000099, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.08%, turnover=89239414. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
