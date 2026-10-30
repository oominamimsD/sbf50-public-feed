# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T15:30:45Z**
- feed_generated_utc: 2026-10-30T15:30:48+00:00
- source_sha256: `0cb790b04f54e8aa1eb0fac05c9c623eb6373ce7a96fdeb1dcf9862a70540f31`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T15:30+00:00, close=77599.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T15:00+00:00, close=77214.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.459400|-16.35|-19.17|-11.28|19718366|2.18|
|CRV_USDT|0.284700|-15.26|-22.48|-10.19|9113650|3.51|
|INJ_USDT|7.170000|-11.82|-9.60|-6.75|32813354|1.40|
|LIT_USDT|2.880100|-11.56|-20.31|-6.49|14641674|0.35|
|LDO_USDT|0.336400|-11.09|-12.05|-6.02|6558483|5.95|
|ETHFI_USDT|0.608900|-10.38|-8.06|-5.31|5967096|1.64|
|TAO_USDT|234.750000|-9.28|-8.88|-4.21|87323473|1.28|
|JUP_USDT|0.256000|-9.15|-17.41|-4.08|7126252|3.90|
|SEI_USDT|0.048560|-9.13|-16.37|-4.06|7392961|2.06|
|TRUMPOFFICIAL_USDT|1.574000|-8.91|-9.74|-3.84|10217613|6.36|
|ZEC_USDT|1245.570000|-8.23|0.91|-3.16|2142517074|0.08|
|SOL_USDT|94.880000|-7.56|-9.27|-2.49|902737413|1.05|
|AVAX_USDT|8.351000|-7.25|-8.89|-2.18|38676919|1.20|
|BNB_USDT|703.600000|-6.44|-3.78|-1.37|57002699|2.84|
|SILVER_USDT|49.410000|-6.13|-10.58|-1.06|435680506|2.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|8.351000|8.183000|8.355000|1.52|N|Y/Y|Y/Y|Y|N|
|BNB_USDT|703.600000|694.700000|703.600000|2.54|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.284700|0.280200|0.285100|0.75|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.608900|0.592200|0.608900|1.37|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.170000|7.034000|7.170000|1.80|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.256000|0.250500|0.256100|4.37|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.336400|0.327900|0.336400|2.80|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.880100|2.728500|2.881400|2.70|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048560|0.047390|0.048560|1.38|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.410000|49.180000|49.440000|0.39|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|94.880000|93.890000|94.930000|3.85|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|234.750000|229.680000|234.680000|4.93|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.459400|0.447400|0.459300|1.59|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.574000|1.538000|1.574000|1.51|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1245.570000|1215.450000|1246.230000|1.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=8.374000, depth_time=2026-10-30T15:30:38+00:00, book20_bid_proxy_usdt=1327647, book20_ask_proxy_usdt=711868, funding_indicative=0.000069, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.25%, turnover=38676919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BNB_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=705.600000, depth_time=2026-10-30T15:30:41+00:00, book20_bid_proxy_usdt=705940, book20_ask_proxy_usdt=1986935, funding_indicative=0.000000, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.44%, turnover=57002699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=0.290000, depth_time=2026-10-30T15:30:10+00:00, book20_bid_proxy_usdt=405870, book20_ask_proxy_usdt=490716, funding_indicative=-0.000109, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.26%, turnover=9113650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=0.609300, depth_time=2026-10-30T15:30:20+00:00, book20_bid_proxy_usdt=232022, book20_ask_proxy_usdt=159808, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.38%, turnover=5967096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=7.178000, depth_time=2026-10-30T15:30:13+00:00, book20_bid_proxy_usdt=276814, book20_ask_proxy_usdt=251464, funding_indicative=0.000094, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.82%, turnover=32813354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=0.256900, depth_time=2026-10-30T15:30:25+00:00, book20_bid_proxy_usdt=483134, book20_ask_proxy_usdt=395711, funding_indicative=0.000015, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.15%, turnover=7126252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=0.337000, depth_time=2026-10-30T15:30:18+00:00, book20_bid_proxy_usdt=328663, book20_ask_proxy_usdt=330965, funding_indicative=0.000073, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.09%, turnover=6558483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=2.917800, depth_time=2026-10-30T15:30:15+00:00, book20_bid_proxy_usdt=25672, book20_ask_proxy_usdt=25127, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.56%, turnover=14641674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=0.048610, depth_time=2026-10-30T15:30:28+00:00, book20_bid_proxy_usdt=197525, book20_ask_proxy_usdt=176959, funding_indicative=0.000028, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.13%, turnover=7392961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=50.050000, depth_time=2026-10-30T15:30:43+00:00, book20_bid_proxy_usdt=48693722, book20_ask_proxy_usdt=53249193, funding_indicative=0.000097, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.13%, turnover=435680506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=96.530000, depth_time=2026-10-30T15:30:36+00:00, book20_bid_proxy_usdt=15154712, book20_ask_proxy_usdt=17271075, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.56%, turnover=902737413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=234.750000, depth_time=2026-10-30T15:30:23+00:00, book20_bid_proxy_usdt=111974, book20_ask_proxy_usdt=78832, funding_indicative=0.000040, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.28%, turnover=87323473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=0.460300, depth_time=2026-10-30T15:30:08+00:00, book20_bid_proxy_usdt=278425, book20_ask_proxy_usdt=324932, funding_indicative=-0.000080, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.35%, turnover=19718366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T15:30:04+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=1.583000, depth_time=2026-10-30T15:30:30+00:00, book20_bid_proxy_usdt=1236501, book20_ask_proxy_usdt=1391506, funding_indicative=-0.000011, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.91%, turnover=10217613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-30T15:30:03+00:00, last15m_closed_end=2026-10-30T15:30+00:00, prior8high=1253.390000, depth_time=2026-10-30T15:30:33+00:00, book20_bid_proxy_usdt=402756, book20_ask_proxy_usdt=106789, funding_indicative=0.000065, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.23%, turnover=2142517074. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
