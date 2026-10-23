# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T00:00:44Z**
- feed_generated_utc: 2026-10-23T00:00:46+00:00
- source_sha256: `43e84c6d4e8484deb8929497a0e6e5516aa3566ed03d49bb0d8e2919b76b027d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.386500|-6.97|9.54|-6.65|13355711|0.29|
|XPL_USDT|0.075520|-3.31|-10.88|-2.99|5590601|3.97|
|PUMPFUN_USDT|0.004548|-3.25|0.48|-2.93|36534144|2.20|
|XMR_USDT|600.900000|-3.16|10.46|-2.84|26638933|0.83|
|STRK_USDT|0.053200|-3.16|-44.79|-2.84|12811368|1.88|
|APT_USDT|0.752700|-3.00|-8.95|-2.68|8856483|2.66|
|QNT_USDT|187.180000|-2.97|-9.97|-2.65|57893939|0.53|
|TIA_USDT|0.558800|-2.93|-7.25|-2.61|22587205|1.79|
|ARB_USDT|0.179030|-2.68|-5.74|-2.36|32064829|0.56|
|EIGEN_USDT|0.217100|-2.29|-12.45|-1.97|5943263|4.61|
|PHA_USDT|0.061230|-2.23|21.19|-1.91|8272462|3.27|
|NEAR_USDT|4.880000|-2.14|-4.66|-1.82|144782319|2.05|
|SEI_USDT|0.057020|-2.09|-7.22|-1.77|9920734|1.75|
|ICP_USDT|2.702000|-1.99|-11.75|-1.67|7894227|3.70|
|UNI_USDT|7.007000|-1.84|-7.13|-1.52|18980890|1.43|
|INJ_USDT|7.907000|-1.80|-1.27|-1.48|28541794|1.26|
|OP_USDT|0.117720|-1.80|-15.23|-1.48|6709048|0.85|
|ZEC_USDT|1218.460000|-1.78|3.28|-1.46|1849004988|0.08|
|ADA_USDT|0.212100|-1.62|-7.98|-1.30|32107052|4.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.752700|0.750100|0.752700|0.47|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.179030|0.177500|0.179030|0.34|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.217100|0.216000|0.217100|0.14|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.702000|2.683000|2.702000|0.47|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.386500|3.395700|3.386500|0.54|N|Y/Y|Y/N|Y|N|
|NEAR_USDT|4.880000|4.848000|4.880000|0.21|N|Y/Y|Y/Y|Y|N|
|PHA_USDT|0.061230|0.060560|0.061280|1.10|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004548|0.004525|0.004548|0.34|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.180000|185.530000|187.180000|0.45|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057020|0.056780|0.057030|0.17|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053200|0.052550|0.053200|0.54|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.558800|0.555400|0.558800|0.59|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.007000|6.969000|7.008000|0.90|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|600.900000|589.510000|600.860000|1.13|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.075520|0.075210|0.075520|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.761600, depth_time=2026-10-23T00:00:20+00:00, book20_bid_proxy_usdt=91194, book20_ask_proxy_usdt=82308, funding_indicative=-0.000056, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=8856483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.181730, depth_time=2026-10-23T00:00:28+00:00, book20_bid_proxy_usdt=73622, book20_ask_proxy_usdt=106889, funding_indicative=-0.000126, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=32064829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.219900, depth_time=2026-10-23T00:00:28+00:00, book20_bid_proxy_usdt=844354, book20_ask_proxy_usdt=537136, funding_indicative=-0.000019, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=5943263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=2.734000, depth_time=2026-10-23T00:00:40+00:00, book20_bid_proxy_usdt=1073942, book20_ask_proxy_usdt=1208109, funding_indicative=-0.000073, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=7894227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=3.508400, depth_time=2026-10-23T00:00:08+00:00, book20_bid_proxy_usdt=28897, book20_ask_proxy_usdt=33175, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=13355711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=4.925000, depth_time=2026-10-23T00:00:35+00:00, book20_bid_proxy_usdt=3021331, book20_ask_proxy_usdt=1550515, funding_indicative=0.000055, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=144782319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.061600, depth_time=2026-10-23T00:00:31+00:00, book20_bid_proxy_usdt=54993, book20_ask_proxy_usdt=75502, funding_indicative=-0.000494, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=8272462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.004649, depth_time=2026-10-23T00:00:13+00:00, book20_bid_proxy_usdt=2027467, book20_ask_proxy_usdt=1758406, funding_indicative=0.000024, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=36534144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=189.080000, depth_time=2026-10-23T00:00:23+00:00, book20_bid_proxy_usdt=90487, book20_ask_proxy_usdt=90948, funding_indicative=-0.000139, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=57893939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.057510, depth_time=2026-10-23T00:00:38+00:00, book20_bid_proxy_usdt=264435, book20_ask_proxy_usdt=354311, funding_indicative=-0.000009, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=9920734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.053160, depth_time=2026-10-23T00:00:14+00:00, book20_bid_proxy_usdt=778717, book20_ask_proxy_usdt=712780, funding_indicative=0.000043, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=12811368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.565100, depth_time=2026-10-23T00:00:25+00:00, book20_bid_proxy_usdt=480429, book20_ask_proxy_usdt=266777, funding_indicative=-0.000012, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=22587205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=7.050000, depth_time=2026-10-23T00:00:42+00:00, book20_bid_proxy_usdt=1538017, book20_ask_proxy_usdt=2060798, funding_indicative=0.000000, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=18980890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T00:00:01+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=601.900000, depth_time=2026-10-23T00:00:16+00:00, book20_bid_proxy_usdt=26713, book20_ask_proxy_usdt=11092, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=26638933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T00:00:02+00:00, last15m_closed_end=2026-10-23T00:00+00:00, prior8high=0.076290, depth_time=2026-10-23T00:00:10+00:00, book20_bid_proxy_usdt=512279, book20_ask_proxy_usdt=560232, funding_indicative=-0.000013, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=5590601. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
