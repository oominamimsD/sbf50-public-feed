# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T13:30:30Z**
- feed_generated_utc: 2026-11-08T13:30:31+00:00
- source_sha256: `0c89218bb0a98d4b54432a23bbb2ee8e76d22296703b3aa47c91653a00b079c8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T13:30+00:00, close=76028.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T13:00+00:00, close=75946.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030266|-9.10|72.74|-9.49|15889456|5.29|
|AKE_USDT|0.005440|-9.07|-51.15|-9.46|28587332|1.84|
|ONE_USDT|0.001894|-6.98|61.34|-7.37|24697714|0.53|
|TIA_USDT|0.422500|-4.32|-13.79|-4.71|7049628|2.37|
|WLD_USDT|0.325700|-2.94|-19.46|-3.33|23871103|3.07|
|ENA_USDT|0.154370|-2.40|-20.43|-2.79|30112151|1.30|
|AAVE_USDT|130.490000|-1.31|-3.70|-1.70|9412018|0.77|
|LINK_USDT|10.743000|-0.93|-7.15|-1.32|63256532|0.93|
|ADA_USDT|0.180300|-0.71|-6.86|-1.10|9989562|5.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.490000|129.980000|130.490000|1.30|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180300|0.179900|0.180300|7.87|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005440|0.005360|0.005440|0.69|N|Y/N|N/N|Y|N|
|ENA_USDT|0.154370|0.152800|0.154360|1.60|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030266|0.027111|0.030266|1.01|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.743000|10.706000|10.743000|1.69|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001894|0.001873|0.001894|0.80|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.422500|0.421400|0.422500|1.36|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.325700|0.324800|0.325700|3.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=131.250000, depth_time=2026-11-08T13:30:17+00:00, book20_bid_proxy_usdt=340393, book20_ask_proxy_usdt=443542, funding_indicative=0.000070, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=9412018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.181000, depth_time=2026-11-08T13:30:29+00:00, book20_bid_proxy_usdt=7966098, book20_ask_proxy_usdt=8031244, funding_indicative=-0.000029, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=9989562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.005818, depth_time=2026-11-08T13:30:11+00:00, book20_bid_proxy_usdt=29308, book20_ask_proxy_usdt=17977, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.07%, turnover=28587332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.155490, depth_time=2026-11-08T13:30:17+00:00, book20_bid_proxy_usdt=229430, book20_ask_proxy_usdt=236811, funding_indicative=-0.000053, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=30112151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.032257, depth_time=2026-11-08T13:30:07+00:00, book20_bid_proxy_usdt=8291, book20_ask_proxy_usdt=4162, funding_indicative=0.000830, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.10%, turnover=15889456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=10.807000, depth_time=2026-11-08T13:30:19+00:00, book20_bid_proxy_usdt=384259, book20_ask_proxy_usdt=306741, funding_indicative=0.000002, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=63256532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.001956, depth_time=2026-11-08T13:30:13+00:00, book20_bid_proxy_usdt=12822, book20_ask_proxy_usdt=17854, funding_indicative=-0.000742, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.98%, turnover=24697714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.427700, depth_time=2026-11-08T13:30:14+00:00, book20_bid_proxy_usdt=249796, book20_ask_proxy_usdt=330338, funding_indicative=-0.000052, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.32%, turnover=7049628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T13:29:59+00:00, last15m_closed_end=2026-11-08T13:30+00:00, prior8high=0.330100, depth_time=2026-11-08T13:30:18+00:00, book20_bid_proxy_usdt=3924079, book20_ask_proxy_usdt=2938982, funding_indicative=-0.000078, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=23871103. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
