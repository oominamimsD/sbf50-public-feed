# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T23:15:34Z**
- feed_generated_utc: 2026-10-17T23:15:36+00:00
- source_sha256: `03b1afaae4fd5c9b45a1d9b187f3f5309164de687775780d31fa37e1c0e25d90`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T23:15+00:00, close=81320.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T23:00+00:00, close=81327, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.172000|-7.12|73.56|-7.12|14687833|5.82|
|DNA_USDT|0.256700|-5.65|UNKNOWN|-5.65|6073151|3.90|
|QNT_USDT|195.000000|-2.69|-20.45|-2.69|65477676|0.51|
|EIGEN_USDT|0.249500|-2.65|5.89|-2.65|10615055|4.01|
|STRK_USDT|0.064570|-2.38|-30.88|-2.38|16135153|1.55|
|FILECOIN_USDT|1.065800|-1.98|-5.49|-1.98|21466101|1.88|
|TIA_USDT|0.645700|-1.86|25.86|-1.86|75466803|3.10|
|ZEC_USDT|1123.550000|-1.55|-8.78|-1.55|1152644128|0.09|
|PUMPFUN_USDT|0.004345|-1.51|-24.10|-1.51|26681079|2.30|
|ARB_USDT|0.181190|-1.48|-2.93|-1.48|30943901|0.55|
|ZRO_USDT|1.862000|-1.23|-7.84|-1.23|8460451|0.54|
|WLD_USDT|0.490300|-1.06|-12.28|-1.06|66359085|2.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181190|0.176600|0.181190|0.81|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.256700|0.245300|0.256700|0.14|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249500|0.241300|0.249500|0.70|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.065800|1.038400|1.065800|0.59|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.172000|0.163200|0.172200|0.30|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004345|0.004262|0.004345|1.16|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.000000|190.470000|194.880000|1.14|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064570|0.063090|0.064570|1.15|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.645700|0.634700|0.645700|0.50|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.490300|0.477800|0.490400|0.95|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1123.550000|1098.000000|1123.650000|0.52|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.862000|1.841200|1.862000|1.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.184600, depth_time=2026-10-17T23:15:29+00:00, book20_bid_proxy_usdt=62505, book20_ask_proxy_usdt=83837, funding_indicative=0.000053, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=30943901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.263400, depth_time=2026-10-17T23:15:08+00:00, book20_bid_proxy_usdt=98702, book20_ask_proxy_usdt=63126, funding_indicative=-0.001457, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.65%, turnover=6073151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.254400, depth_time=2026-10-17T23:15:15+00:00, book20_bid_proxy_usdt=444447, book20_ask_proxy_usdt=488767, funding_indicative=0.000010, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=10615055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=1.098300, depth_time=2026-10-17T23:15:18+00:00, book20_bid_proxy_usdt=534518, book20_ask_proxy_usdt=1085197, funding_indicative=-0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=21466101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.192300, depth_time=2026-10-17T23:15:07+00:00, book20_bid_proxy_usdt=368378, book20_ask_proxy_usdt=147134, funding_indicative=-0.000212, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.12%, turnover=14687833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.004473, depth_time=2026-10-17T23:15:27+00:00, book20_bid_proxy_usdt=1738999, book20_ask_proxy_usdt=1691217, funding_indicative=0.000023, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=26681079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=200.290000, depth_time=2026-10-17T23:15:12+00:00, book20_bid_proxy_usdt=55494, book20_ask_proxy_usdt=90938, funding_indicative=-0.000064, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=65477676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.065190, depth_time=2026-10-17T23:15:17+00:00, book20_bid_proxy_usdt=493334, book20_ask_proxy_usdt=435463, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=16135153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.670900, depth_time=2026-10-17T23:15:21+00:00, book20_bid_proxy_usdt=208229, book20_ask_proxy_usdt=171341, funding_indicative=-0.000029, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=75466803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=0.506800, depth_time=2026-10-17T23:15:34+00:00, book20_bid_proxy_usdt=1731550, book20_ask_proxy_usdt=1666337, funding_indicative=-0.000098, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=66359085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=1162.560000, depth_time=2026-10-17T23:15:24+00:00, book20_bid_proxy_usdt=483808, book20_ask_proxy_usdt=273559, funding_indicative=0.000036, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=1152644128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T23:15:02+00:00, last15m_closed_end=2026-10-17T23:15+00:00, prior8high=1.913500, depth_time=2026-10-17T23:15:31+00:00, book20_bid_proxy_usdt=25577, book20_ask_proxy_usdt=54347, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=8460451. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
